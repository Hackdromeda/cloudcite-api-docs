---
description: >-
  The Style Search API returns a list of styles supported by CSL with details
  about each style.
---

# Style Search API

{% api-method method="post" host="https://api.cloudcite.net" path="/style" %}
{% api-method-summary %}
Style
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

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=304 %}
{% api-method-response-example-description %}
The response you have cached hasn't changed.
{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=401 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=403 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=422 %}
{% api-method-response-example-description %}
You are missing a required field in the request body.
{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=500 %}
{% api-method-response-example-description %}
Something went wrong. Check the request body you sent us.
{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% code-tabs %}
{% code-tabs-item title="Style Search Request" %}
```javascript
{
    "search":"query"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Style Search Response - \"MLA\"" %}
```
[{
    "title": "Modern Language Association 6th edition (note)",
    "titleShort": "MLA",
    "name": "modern-language-association-6th-edition-note",
    "dependent": 0,
    "categories": {
        "format": "note",
        "fields": ["generic-base"]
    },
    "updated": "2017-12-06 03:34:05",
    "filename": "modern-language-association-6th-edition-note"
}, {
    "title": "Modern Language Association 7th edition",
    "titleShort": "MLA",
    "name": "modern-language-association-7th-edition",
    "dependent": 0,
    "categories": {
        "format": "author",
        "fields": ["generic-base"]
    },
    "updated": "2017-09-29 03:07:06",
    "filename": "modern-language-association-7th-edition"
}, {
    "title": "Modern Language Association 7th edition (underline)",
    "titleShort": "MLA",
    "name": "modern-language-association-7th-edition-underline",
    "dependent": 0,
    "categories": {
        "format": "author",
        "fields": ["generic-base"]
    },
    "updated": "2017-09-29 03:07:06",
    "filename": "modern-language-association-7th-edition-underline"
}, {
    "title": "Modern Language Association 7th edition (with URL)",
    "titleShort": "MLA",
    "name": "modern-language-association-7th-edition-with-url",
    "dependent": 0,
    "categories": {
        "format": "author",
        "fields": ["generic-base"]
    },
    "updated": "2017-09-29 03:07:06",
    "filename": "modern-language-association-7th-edition-with-url"
}, {
    "title": "Modern Language Association 8th edition",
    "titleShort": "MLA",
    "name": "modern-language-association",
    "dependent": 0,
    "categories": {
        "format": "author",
        "fields": ["generic-base"]
    },
    "updated": "2018-01-09 14:13:59",
    "filename": "modern-language-association"
}, {
    "title": "University of York - Modern Language Association 8th edition",
    "titleShort": "UoY MLA",
    "name": "university-of-york-mla",
    "dependent": 0,
    "categories": {
        "format": "author",
        "fields": ["generic-base"]
    },
    "updated": "2017-10-26 23:59:09",
    "filename": "university-of-york-mla"
}]
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## How do I interpret the response?

* `title` \(string\): Full name of citation style
* `titleShort` \(string\): Abbreviation or acronym for citation style, not always available
* `dependent` \(integer\): Related to another citation style if 1. In this case, the style is located in `./dependent/`.
* `name` and `filename` \(string\): The name of the `.csl` file.
* `updated` \(date object\): JavaScript date object for date when the style was updated.

## Supported Styles

A full list of supported styles can be found [HERE](https://cloudcite.net/static/styles.txt).

