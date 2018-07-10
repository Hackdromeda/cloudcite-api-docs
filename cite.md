---
description: >-
  Autofill accepts a CSL-JSON body with a specified citation style and locale
  and returns a formatted citation.
---

# Cite

## Endpoint

You need to make POST requests to this endpoint. The body content type must be APPLICATION/JSON.

```http
https://api.cloudcite.net/cite
```

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

