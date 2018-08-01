---
description: >-
  Citation Style Language's goal is to facilitate scholarly publishing by
  automating the formatting of citations and bibliographies. Learn more at
  https://citationstyles.org/.
---

# Citation Style Language \(CSL\)

## Where I can learn more about CSL?

You can learn more on their [official website](https://citationstyles.org/).

## What is CSL-JSON, the CSL Data Schema, and the CSL Citation Schema? When do I use each?

CSL-JSON is the JSON data model for storing CSL processor input and output. 

[CSL-JSON Data](https://github.com/citation-style-language/schema/blob/master/csl-data.json) is a JSON schema for CSL input data.  This is what you provide the CSL engine to create a citation which it returns in formatted HTML. To learn more in depth about these fields and how to use them, refer to the [CiteProc documentation](https://citeproc-js.readthedocs.io/en/latest/csl-json/markup.html) and [Zotero documentation](https://aurimasv.github.io/z2csl/).

[CSL-JSON Citation](https://github.com/citation-style-language/schema/blob/master/csl-citation.json) is a JSON schema for CSL citation objects. This is what you provide the CSL engine to process citation clusters with citation IDs you have already sent data for in the same session. To learn more about these fields and how to use them, refer to the [CiteProc Documentation](https://citeproc-js.readthedocs.io/en/latest/csl-json/markup.html#citations).

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Citation" %}
```text
{
   "citationItems": [
      {
         "id": "ITEM-1"
      }
   ],
   "properties": {
      "noteIndex": 1
   }
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="CSL-JSON Data" %}
```
{
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
```
{% endcode-tabs-item %}
{% endcode-tabs %}

