---
description: >-
  The Citation Formatting API accepts a CSL-JSON body with a specified citation
  style and locale and returns a formatted citation.
---

# Citation Formatting API

{% api-method method="post" host="https://api.cloudcite.net" path="/cite" %}
{% api-method-summary %}
Cite
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="x-api-key" type="string" required=true %}
Your API Key
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-body-parameters %}
{% api-method-parameter name="Request" type="object" required=true %}
Use the request formats below
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
It worked!
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=304 %}
{% api-method-response-example-description %}
The response you have cached hasn't changed.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=401 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=403 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=422 %}
{% api-method-response-example-description %}
You are missing a required field in the request body.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=500 %}
{% api-method-response-example-description %}
Something went wrong. Check the request body you sent us.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## How It Works

Cite requires the following to be sent in the body of the POST request:

{% code-tabs %}
{% code-tabs-item title="Cite Request Fields - MLA, en-US" %}
```
{
    style: "modern-language-association",
    locale: "locales-en-US",
    csl: <csl>
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Cite Request Example - MLA, en-US" %}
```
{
    "style": "modern-language-association",
    "locale": "locales-en-US",
    "csl": {
        "SET-YOUR-OWN-ID": {
            "issued": {
                "year": "1953"
            },
            "id": "SET-YOUR-OWN-ID",
            "author": [{
                "given": "Tennessee",
                "family": "Williams"
            }],
            "title": "A Streetcar Named Desire",
            "publisher": "Dramatists Play Service Inc",
            "ISBN": "9780822210894",
            "number-of-pages": 107,
            "dimensions": "20.00 cm x 12.70 cm x 0.60 cm",
            "abstract": "THE STORY: The play reveals to the very depths the character of Blanche du Bois, a woman whose life has been undermined by her romantic illusions, which lead her to reject--so far as possible--the realities of life with which she is faced and which s",
            "type": "book"
        },
        "SET":{
            "issued": {
                "month": "04",
                "year": "2018",
                "day": "25"
            },
            "id": "SET",
            "director": [{
                "given": "Joe",
                "family": "Russo"
            }, {
                "given": "Anthony",
                "family": "Russo"
            }],
            "title": "Avengers: Infinity War",
            "publisher": "Walt Disney Pictures",
            "publisher-place": "United States of America",
            "source": null,
            "abstract": "As the Avengers and their allies have continued to protect the world from threats too large for any one hero to handle, a new danger has emerged from the cosmic shadows: Thanos. A despot of intergalactic infamy, his goal is to collect all six Infinity Stones, artifacts of unimaginable power, and use them to inflict his twisted will on all of reality. Everything the Avengers have fought for has led up to this moment - the fate of Earth and existence itself has never been more uncertain.",
            "type": "motion_picture"
        }
    }
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Cite will send the following back

{% code-tabs %}
{% code-tabs-item title="Cite Response - MLA, en-US" %}
```
[{
        "maxoffset": 0,
        "entryspacing": 0,
        "linespacing": 2,
        "second-field-align": false,
        "entry_ids": [
            ["SET"],
            ["SET-YOUR-OWN-ID"]
        ],
        "bibliography_errors": [],
        "done": false,
        "hangingindent": 2,
        "bibstart": "<div class=\"csl-bib-body\">\n",
        "bibend": "</div>"
    },
    [
    "  <div class=\"csl-entry\"><i>Avengers: Infinity War</i>. Walt Disney Pictures, 2018.</div>\n",
    "  <div class=\"csl-entry\">Williams, Tennessee. <i>A Streetcar Named Desire</i>. Dramatists Play Service Inc, 1953.</div>\n"
    ]
]
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## How do I interpret the response?

* `maxoffset` \(integer\): The width of the widest first field in the bibliography, measured in characters.
* `linespacing` \(integer\): Vertical line distance specified as a multiple of standard line height. You can force a minimum if there is none assigned such as **1.35**.
* `entryspacing` \(integer\): Vertical distance between bibliographic entries, specified as a multiple of standard line height.
* `second-field-align` \(boolean or integer\): The position of second-field alignment.
* `hangingindent` \(boolean or integer\): Whether the bibliography items should be rendered with hanging-indents and the size of the indent.
* `rightpadding` \(constant\): **.5**
* Each entry is assigned a CSS class. You apply properties based on the class assigned by CSL.

### Example HTML

```markup
<div class="csl-bib-body">
  <div class="csl-entry">
    <div class="csl-left-margin">[1]</div>
    <div class="csl-right-inline">M. Krämer, “citeproc-java: A Citation Style
      Language (CSL) processor for Java,” 20-Nov-2016. [Online]. Available:
      http://michel-kraemer.github.io/citeproc-java/. [Accessed: 29-Jul-2018].
    </div>
  </div>
  <div class="csl-entry">
    Williams, Tennessee. <i>A Streetcar Named Desire</i>. Dramatists Play Service Inc, 1953.
  </div>
</div>
```

### **Example CSS**

**For an example of how to add CSS to these classes,** [**go to the Zotero repository**](https://github.com/zotero/bib-web/blob/97567c6c1680e05f740303ad8148aed89c965639/src/js/cite.js)**. Here's a basic overview:**

#### Here's what your CSS should look like for an the `csl-bib-body` class:

```css
 'line-height: ' + linespacing + '; '
```

If the container has no child with the csl-left margin class and a hanging indent, add the following CSS. Note CSS properties when second-field-align=false or no value and hangingindent=true or value combination is not currently supported by this logic.

```css
'margin-left: ' + hangingindent + 'em; text-indent:-' + hangingindent + 'em;'
```

#### Here's what your CSS should look like for an the `csl-entry` class:

```css
'clear: left; margin-bottom:' + entryspacing + 'em;'
```

If you want to prevent text overflow such as with links, consider adding:

```css
'word-break: break-all;'
```

#### Here's what your CSS should look like for an the `csl-indent` class.

```css
'margin: .5em 0 0 2em; padding: 0 0 .2em .5em; border-left: 5px solid #ccc;'
```

#### Here's what your CSS should look like for an the `csl-right-inline` class:

```css
'margin: 0 .4em 0 ' + (secondFieldAlign ? maxOffset + rightPadding : '0') + 'em;'
```

If there's a hanging indent, add:

```css
'padding-left: ' + hangingindent + 'em; text-indent:-' + hangingindent + 'em;'
```

#### Here's what your CSS should look like for an the `csl-left-margin` class:

```css
'float: left; padding-right: ' + rightpadding + 'em;'
```

If there's a second-field-align value or it is true, add this:

```css
'text-align: right; width: ' + maxoffset + 'em;'
```



