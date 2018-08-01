---
description: >-
  The Metadata Autofill API provides a CSL-JSON response when you provide it
  with the specific website, book, or movie.
---

# Metadata Autofill API

{% api-method method="post" host="https://api.cloudcite.net" path="/autofill" %}
{% api-method-summary %}
Autofill
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

## Websites

Autofill requires the following fields to be sent in the body of the POST request:

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Request" %}
```
{
  "url": "https://www.theguardian.com/news/2018/jun/29/the-great-firewall-of-china-xi-jinpings-internet-shutdown",
  "format": "website",
  "id": "CITATION-1"
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Here's how it will respond:

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Response" %}
```
{
    "issued": {
        "month": "6",
        "year": "2018",
        "day": "29"
    },
    "id": "CITATION-1",
    "author": [{
        "given": "Elizabeth C",
        "family": "Economy"
    }],
    "title": "The great firewall of China: Xi Jinping’s internet shutdown",
    "publisher": "Guardian News and Media Limited",
    "source": "the Guardian",
    "URL": "https://www.theguardian.com/news/2018/jun/29/the-great-firewall-of-china-xi-jinpings-internet-shutdown",
    "abstract": "The long read: Before Xi Jinping, the internet was becoming a more vibrant political space for Chinese citizens. But today the country has the largest and most sophisticated online censorship operation in the world",
    "type": "webpage"
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Books

Autofill requires the following fields to be sent in the body of the POST request. The "book" field is the unique ID Google Books assigns to the volume. You may make a search request to get the unique ID. You can search using ONE of the following: title, ISBN, OCLC, LCCN, author name, or publisher name.

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Request" %}
```
{
  "title": "The Street Car Named Desire",
  "book": "44qi9P-COd4C",
  "format": "book"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Request" %}
```text
{
  "title": "The Street Car Named Desire",
  "isbn": "ISBN number, no dashes",
  "oclc": "Online Computer Library Center number",
  "lccn": "Library of Congress Control Number",
  "author": "Author",
  "publisher": "Publisher",
  "book": "",
  "format": "book"
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Here's how it will respond:

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Response" %}
```
{
    "issued": {
        "month": null,
        "year": "1953",
        "day": null
    },
    "id": "SET",
    "author": [{
        "given": "Tennessee",
        "family": "Williams"
    }],
    "editor": [],
    "collection-editor": [],
    "translator": [],
    "edition": null,
    "language": "English",
    "title": "A Streetcar Named Desire",
    "title-short": null,
    "publisher": "Dramatists Play Service Inc",
    "publisher-place": null,
    "ISBN": "9780822210894",
    "number-of-pages": 107,
    "number-of-volumes": null,
    "source": null,
    "URL": null,
    "dimensions": "20.00 cm x 12.70 cm x 0.60 cm",
    "abstract": "THE STORY: The play reveals to the very depths the character of Blanche du Bois, a woman whose life has been undermined by her romantic illusions, which lead her to reject--so far as possible--the realities of life with which she is faced and which s",
    "collection-title": null,
    "type": "book"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Response" %}
```
{
    "kind": "books#volumes",
    "totalItems": 1438,
    "items": [{
            "kind": "books#volume",
            "id": "44qi9P-COd4C",
            "etag": "UMzIDPf6fcY",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/44qi9P-COd4C",
            "volumeInfo": {
                "title": "A Streetcar Named Desire",
                "subtitle": "Play in Three Acts",
                "authors": [
                    "Tennessee Williams"
                ],
                "publisher": "Dramatists Play Service Inc",
                "publishedDate": "1953",
                "description": "Tennessee Williams' classic drama studies the emotional disintegration of a Southern woman whose last chance for happiness is destroyed by her vindictive brother-in-law.",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "0822210894"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9780822210894"
                    }
                ],
                "readingModes": {
                    "text": false,
                    "image": true
                },
                "pageCount": 107,
                "printType": "BOOK",
                "categories": [
                    "Drama"
                ],
                "averageRating": 4.0,
                "ratingsCount": 44,
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "0.0.1.0.preview.1",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=44qi9P-COd4C&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=44qi9P-COd4C&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=44qi9P-COd4C&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=1&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=44qi9P-COd4C&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/A_Streetcar_Named_Desire.html?hl=&id=44qi9P-COd4C"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": false
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=44qi9P-COd4C&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "Tennessee Williams&#39; classic drama studies the emotional disintegration of a Southern woman whose last chance for happiness is destroyed by her vindictive brother-in-law."
            }
        },
        {
            "kind": "books#volume",
            "id": "uZzCbwAACAAJ",
            "etag": "AmndOG0gZ+8",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/uZzCbwAACAAJ",
            "volumeInfo": {
                "title": "A Streetcar Named Desire",
                "authors": [
                    "Tennessee Williams",
                    "Nicola Onyett"
                ],
                "publisher": "Hodder Education",
                "publishedDate": "2011-02-01",
                "description": "Written by experienced A-level examiners and teachers who know exactly what students need to succeed, and edited by a chief examiner, Philip Allan Literature Guides are invaluable study companions for senior students with exam-specific advice to help you to get the grade you need. This full colour guide includes: - detailed scene summaries and sections on themes, characters, form, structure, language and contexts - a dedicated 'Working with the text' section on how to write about texts for coursework and controlled assessment and how to revise for exams - Taking it further boxes on related books, film adaptations and websites - Pause for thought boxes to get you thinking more widely about the text - Task boxes to test yourself on transformation, analysis, research and comparison activities - Top 10 quotes",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "1444121561"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9781444121568"
                    }
                ],
                "readingModes": {
                    "text": false,
                    "image": false
                },
                "pageCount": 94,
                "printType": "BOOK",
                "categories": [
                    "Juvenile Fiction"
                ],
                "averageRating": 4.0,
                "ratingsCount": 43,
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "preview-1.0.0",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=uZzCbwAACAAJ&printsec=frontcover&img=1&zoom=5&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=uZzCbwAACAAJ&printsec=frontcover&img=1&zoom=1&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=uZzCbwAACAAJ&dq=The+Street+Car+Named+Desire&hl=&cd=2&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=uZzCbwAACAAJ&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/A_Streetcar_Named_Desire.html?hl=&id=uZzCbwAACAAJ"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "NO_PAGES",
                "embeddable": false,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": false
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=uZzCbwAACAAJ&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "NONE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "For study or revision, these guides are the perfect accompaniment to the set text, providing invaluable background and exam advice."
            }
        },
        {
            "kind": "books#volume",
            "id": "gWcDODllqSIC",
            "etag": "2vX2Hm/ZGMU",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/gWcDODllqSIC",
            "volumeInfo": {
                "title": "A Streetcar Named Desire",
                "authors": [
                    "Tennessee Williams",
                    "Michael Hooper",
                    "Patricia Hern"
                ],
                "publisher": "A&amp;C Black",
                "publishedDate": "2009-02-24",
                "description": "A comprehensively revised student edition of this classic play which depicts a turbulent confrontation between traditional values in the American South and the rough-edged, aggressive materialism of the new world.",
                "industryIdentifiers": [{
                        "type": "ISBN_13",
                        "identifier": "9781408106044"
                    },
                    {
                        "type": "ISBN_10",
                        "identifier": "1408106043"
                    }
                ],
                "readingModes": {
                    "text": true,
                    "image": false
                },
                "pageCount": 208,
                "printType": "BOOK",
                "categories": [
                    "Drama"
                ],
                "averageRating": 4.0,
                "ratingsCount": 43,
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "0.0.2.0.preview.2",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=gWcDODllqSIC&printsec=frontcover&img=1&zoom=5&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=gWcDODllqSIC&printsec=frontcover&img=1&zoom=1&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=gWcDODllqSIC&dq=The+Street+Car+Named+Desire&hl=&cd=3&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=gWcDODllqSIC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/A_Streetcar_Named_Desire.html?hl=&id=gWcDODllqSIC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "NO_PAGES",
                "embeddable": false,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": true
                },
                "pdf": {
                    "isAvailable": true
                },
                "webReaderLink": "http://play.google.com/books/reader?id=gWcDODllqSIC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "NONE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "A comprehensively revised student edition of this classic play which depicts a turbulent confrontation between traditional values in the American South and the rough-edged, aggressive materialism of the new world."
            }
        },
        {
            "kind": "books#volume",
            "id": "_2Oo7l5fayAC",
            "etag": "b2T1Kbvw+hU",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/_2Oo7l5fayAC",
            "volumeInfo": {
                "title": "Alex North's A Streetcar Named Desire",
                "subtitle": "A Film Score Guide",
                "authors": [
                    "Annette Davison"
                ],
                "publisher": "Scarecrow Press",
                "publishedDate": "2009",
                "description": "This film score handbook provides a detailed analysis of Alex North's astounding score for Elia Kazan's 1951 adaptation of A Streetcar Named Desire. Beginning with a review of North's musical training and film scoring techniques, the book then uses approaches from both musicology and film studies to present a comprehensive exploration of the film's (self-)censorship and its impact on North's music, most notably in the film's infamous staircase scene.",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "0810863936"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9780810863934"
                    }
                ],
                "readingModes": {
                    "text": true,
                    "image": true
                },
                "pageCount": 229,
                "printType": "BOOK",
                "categories": [
                    "Music"
                ],
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "0.0.1.0.preview.3",
                "panelizationSummary": {
                    "containsEpubBubbles": false,
                    "containsImageBubbles": false
                },
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=_2Oo7l5fayAC&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=_2Oo7l5fayAC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=_2Oo7l5fayAC&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=4&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=_2Oo7l5fayAC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/Alex_North_s_A_Streetcar_Named_Desire.html?hl=&id=_2Oo7l5fayAC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": true,
                    "acsTokenLink": "http://books.google.com/books/download/Alex_North_s_A_Streetcar_Named_Desire-sample-epub.acsm?id=_2Oo7l5fayAC&format=epub&output=acs4_fulfillment_token&dl_type=sample&source=gbs_api"
                },
                "pdf": {
                    "isAvailable": true,
                    "acsTokenLink": "http://books.google.com/books/download/Alex_North_s_A_Streetcar_Named_Desire-sample-pdf.acsm?id=_2Oo7l5fayAC&format=pdf&output=acs4_fulfillment_token&dl_type=sample&source=gbs_api"
                },
                "webReaderLink": "http://play.google.com/books/reader?id=_2Oo7l5fayAC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "This film score handbook provides a detailed analysis of Alex North&#39;s astounding score for Elia Kazan&#39;s 1951 adaptation of A Streetcar Named Desire."
            }
        },
        {
            "kind": "books#volume",
            "id": "AnQy2tnbQJMC",
            "etag": "n4Fntkwvrd0",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/AnQy2tnbQJMC",
            "volumeInfo": {
                "title": "Tennessee Williams's The Glass Menagerie & A Streetcar Named Desire",
                "authors": [
                    "George Ehrenhaft",
                    "Tennessee Williams"
                ],
                "publisher": "Barron's Educational Series",
                "publishedDate": "1985",
                "description": "A guide to reading \"The Glass Menagerie\" and \"A Streetcar Named Desire\" with a critical and appreciative mind encouraging analysis of plot, style, form, and structure. Also includes background on the author's life and times, sample tests, term paper suggestions, and a reading list.",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "081203516X"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9780812035162"
                    }
                ],
                "readingModes": {
                    "text": true,
                    "image": true
                },
                "pageCount": 122,
                "printType": "BOOK",
                "categories": [
                    "American literature"
                ],
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "preview-1.0.0",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=AnQy2tnbQJMC&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=AnQy2tnbQJMC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=AnQy2tnbQJMC&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=5&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=AnQy2tnbQJMC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/Tennessee_Williams_s_The_Glass_Menagerie.html?hl=&id=AnQy2tnbQJMC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": true,
                    "acsTokenLink": "http://books.google.com/books/download/Tennessee_Williams_s_The_Glass_Menagerie-sample-epub.acsm?id=AnQy2tnbQJMC&format=epub&output=acs4_fulfillment_token&dl_type=sample&source=gbs_api"
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=AnQy2tnbQJMC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "A guide to reading &quot;The Glass Menagerie&quot; and &quot;A Streetcar Named Desire&quot; with a critical and appreciative mind encouraging analysis of plot, style, form, and structure."
            }
        },
        {
            "kind": "books#volume",
            "id": "duVcT5J4qWIC",
            "etag": "f3F3i69O52g",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/duVcT5J4qWIC",
            "volumeInfo": {
                "title": "Williams: A Streetcar Named Desire",
                "authors": [
                    "Philip C. Kolin"
                ],
                "publisher": "Cambridge University Press",
                "publishedDate": "2000-04-27",
                "description": "A continuous history of the play, Streetcar named desire in production from 1947 to 1998, with emphasis on the Broadway premiere.",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "0521626102"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9780521626101"
                    }
                ],
                "readingModes": {
                    "text": false,
                    "image": true
                },
                "pageCount": 229,
                "printType": "BOOK",
                "categories": [
                    "Drama"
                ],
                "averageRating": 4.0,
                "ratingsCount": 1,
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "1.0.0.0.preview.1",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=duVcT5J4qWIC&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=duVcT5J4qWIC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=duVcT5J4qWIC&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=6&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=duVcT5J4qWIC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/Williams_A_Streetcar_Named_Desire.html?hl=&id=duVcT5J4qWIC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": false
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=duVcT5J4qWIC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "A continuous history of the play, Streetcar named desire in production from 1947 to 1998, with emphasis on the Broadway premiere."
            }
        },
        {
            "kind": "books#volume",
            "id": "VcyFkNOYsFgC",
            "etag": "F6DdRNNffwA",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/VcyFkNOYsFgC",
            "volumeInfo": {
                "title": "A Streetcar Named Desire",
                "authors": [
                    "Tennessee Williams"
                ],
                "publisher": "New Directions Publishing",
                "publishedDate": "1947",
                "description": "Tennessee Williams' classic drama studies the emotional disintegration of a Southern woman whose last chance for happiness is destroyed by her vindictive brother-in-law.",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "0811216020"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9780811216029"
                    }
                ],
                "readingModes": {
                    "text": false,
                    "image": true
                },
                "pageCount": 192,
                "printType": "BOOK",
                "categories": [
                    "Drama"
                ],
                "averageRating": 4.0,
                "ratingsCount": 48,
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "preview-1.0.0",
                "panelizationSummary": {
                    "containsEpubBubbles": false,
                    "containsImageBubbles": false
                },
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=VcyFkNOYsFgC&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=VcyFkNOYsFgC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=VcyFkNOYsFgC&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=7&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=VcyFkNOYsFgC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/A_Streetcar_Named_Desire.html?hl=&id=VcyFkNOYsFgC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": false
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=VcyFkNOYsFgC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "Tennessee Williams&#39; classic drama studies the emotional disintegration of a Southern woman whose last chance for happiness is destroyed by her vindictive brother-in-law."
            }
        },
        {
            "kind": "books#volume",
            "id": "UnttQgAACAAJ",
            "etag": "hpJSe+pI6bA",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/UnttQgAACAAJ",
            "volumeInfo": {
                "title": "A Streetcar Named Desire",
                "subtitle": "And Other Plays",
                "authors": [
                    "Tennessee Williams"
                ],
                "publishedDate": "1962-01",
                "description": "For use in schools and libraries only. Tennessee Williams' classic drama studies the emotional disintegration of a Southern woman whose last chance for happiness is destroyed by her vindictive brother-in-law.",
                "industryIdentifiers": [{
                        "type": "ISBN_10",
                        "identifier": "014018385X"
                    },
                    {
                        "type": "ISBN_13",
                        "identifier": "9780140183856"
                    }
                ],
                "readingModes": {
                    "text": false,
                    "image": false
                },
                "pageCount": 313,
                "printType": "BOOK",
                "categories": [
                    "American drama"
                ],
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "preview-1.0.0",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=UnttQgAACAAJ&printsec=frontcover&img=1&zoom=5&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=UnttQgAACAAJ&printsec=frontcover&img=1&zoom=1&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=UnttQgAACAAJ&dq=The+Street+Car+Named+Desire&hl=&cd=8&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=UnttQgAACAAJ&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/A_Streetcar_Named_Desire.html?hl=&id=UnttQgAACAAJ"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "NO_PAGES",
                "embeddable": false,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": false
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=UnttQgAACAAJ&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "NONE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "For use in schools and libraries only. Tennessee Williams&#39; classic drama studies the emotional disintegration of a Southern woman whose last chance for happiness is destroyed by her vindictive brother-in-law."
            }
        },
        {
            "kind": "books#volume",
            "id": "_uEc3SjfqUMC",
            "etag": "2DR1+Q93s9w",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/_uEc3SjfqUMC",
            "volumeInfo": {
                "title": "A Streetcar Named Desire",
                "authors": [
                    "Harold Bloom"
                ],
                "publisher": "Infobase Publishing",
                "publishedDate": "2009-01-01",
                "description": "Discusses the writing of A streetcar named Desire by Tennessee Williams. Includes critical essays on the work and a brief biography of the author.",
                "industryIdentifiers": [{
                        "type": "ISBN_13",
                        "identifier": "9781438114811"
                    },
                    {
                        "type": "ISBN_10",
                        "identifier": "1438114818"
                    }
                ],
                "readingModes": {
                    "text": true,
                    "image": true
                },
                "pageCount": 143,
                "printType": "BOOK",
                "categories": [
                    "New Orleans (La.)"
                ],
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "0.0.1.0.preview.3",
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=_uEc3SjfqUMC&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=_uEc3SjfqUMC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=_uEc3SjfqUMC&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=9&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=_uEc3SjfqUMC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/A_Streetcar_Named_Desire.html?hl=&id=_uEc3SjfqUMC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": true,
                    "acsTokenLink": "http://books.google.com/books/download/A_Streetcar_Named_Desire-sample-epub.acsm?id=_uEc3SjfqUMC&format=epub&output=acs4_fulfillment_token&dl_type=sample&source=gbs_api"
                },
                "pdf": {
                    "isAvailable": true,
                    "acsTokenLink": "http://books.google.com/books/download/A_Streetcar_Named_Desire-sample-pdf.acsm?id=_uEc3SjfqUMC&format=pdf&output=acs4_fulfillment_token&dl_type=sample&source=gbs_api"
                },
                "webReaderLink": "http://play.google.com/books/reader?id=_uEc3SjfqUMC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "Discusses the writing of A streetcar named Desire by Tennessee Williams. Includes critical essays on the work and a brief biography of the author."
            }
        },
        {
            "kind": "books#volume",
            "id": "ZOYQB2m-kFcC",
            "etag": "lgVZhQVxY0c",
            "selfLink": "https://www.googleapis.com/books/v1/volumes/ZOYQB2m-kFcC",
            "volumeInfo": {
                "title": "Reality and Illusion in Tennessee Williams' Âa Streetcar Named Desire",
                "authors": [
                    "Ilona Sontag"
                ],
                "publisher": "GRIN Verlag",
                "publishedDate": "2010-03",
                "description": "Seminar paper from the year 2009 in the subject English - Literature, Works, grade: 1,7, RWTH Aachen University (Institut fur Anglistik I), course: Hauptseminar \"American Drama,\" language: English, abstract: Tennessee Williams, born Thomas Lanier Williams, is not only known for being a \"talented, perceptive and influential American playwright\" (Day 1987, vii), but also for his frequent use of symbols. \"A Streetcar Named Desire\" (1947), the work which will be dealt with in this paper, is a good example for of usage, since it contains a lot of different kinds of symbolism, for example concerning colours, names, music and many more. Numerous works will be found, if anyone searches for essays about symbolism in Williams' works. Moreover, it is common knowledge that Streetcar is a play which deals not only superficially with a woman going insane, but a play which \"bring s] into violent contrast a neurotic woman's dream world and the animalistic realism of her brother-in-law\" (back of the book in the Diesterweg edition). But since there does not seem to be any work which deals with the question of how exactly Williams drew this contrast by use of symbolism, it will be my aim in this paper to analyse this question. Consequently, I will try to point out the main symbols with which Williams underlined the contrast between realism and illusion, especially considering names, colours, clothes, light, music and certain rituals of the main characters. In the second part of this paper, I will deal with the question to what degree the main characters Stanley and Blanche are strictly opposed to each other or may have something in common. I will also deal with the meaning of the ending concerning realism and illusion. Therefore, what will be discussed are the most striking antinomies and similes in the main characters' attitudes. A general conclusion about the topic of symbolism in Tennessee Williams' Streetcar will be given in the end. To introduce the reader to the topic an\"",
                "industryIdentifiers": [{
                        "type": "ISBN_13",
                        "identifier": "9783640559251"
                    },
                    {
                        "type": "ISBN_10",
                        "identifier": "3640559258"
                    }
                ],
                "readingModes": {
                    "text": false,
                    "image": true
                },
                "pageCount": 28,
                "printType": "BOOK",
                "maturityRating": "NOT_MATURE",
                "allowAnonLogging": false,
                "contentVersion": "0.2.4.0.preview.1",
                "panelizationSummary": {
                    "containsEpubBubbles": false,
                    "containsImageBubbles": false
                },
                "imageLinks": {
                    "smallThumbnail": "http://books.google.com/books/content?id=ZOYQB2m-kFcC&printsec=frontcover&img=1&zoom=5&edge=curl&source=gbs_api",
                    "thumbnail": "http://books.google.com/books/content?id=ZOYQB2m-kFcC&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api"
                },
                "language": "en",
                "previewLink": "http://books.google.com/books?id=ZOYQB2m-kFcC&printsec=frontcover&dq=The+Street+Car+Named+Desire&hl=&cd=10&source=gbs_api",
                "infoLink": "http://books.google.com/books?id=ZOYQB2m-kFcC&dq=The+Street+Car+Named+Desire&hl=&source=gbs_api",
                "canonicalVolumeLink": "https://books.google.com/books/about/Reality_and_Illusion_in_Tennessee_Willia.html?hl=&id=ZOYQB2m-kFcC"
            },
            "saleInfo": {
                "country": "US",
                "saleability": "NOT_FOR_SALE",
                "isEbook": false
            },
            "accessInfo": {
                "country": "US",
                "viewability": "PARTIAL",
                "embeddable": true,
                "publicDomain": false,
                "textToSpeechPermission": "ALLOWED",
                "epub": {
                    "isAvailable": false
                },
                "pdf": {
                    "isAvailable": false
                },
                "webReaderLink": "http://play.google.com/books/reader?id=ZOYQB2m-kFcC&hl=&printsec=frontcover&source=gbs_api",
                "accessViewStatus": "SAMPLE",
                "quoteSharingAllowed": false
            },
            "searchInfo": {
                "textSnippet": "&quot;A Streetcar Named Desire&quot; (1947), the work which will be dealt with in this paper, is a good example for of usage, since it contains a lot of different kinds of symbolism, for example concerning colours, names, music and many more."
            }
        }
    ]
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Music

Autofill requires the following fields to be sent in the body of the POST request. Music has the following types: `album`, `song`, and `song-in-album`. You can use `song-in-album` once you have chosen the `collectionId` of the album you want the songs for. You can use the `trackId` of the song once you have chosen the song you want the CSL-JSON data for.

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Song Request" %}
```
{
  "title": "In My Feelings",
  "format": "music",
  "type": "song",
  "song": "1418213402"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="CSL-JSON Data Album Request" %}
```
{
  "title": "DAMN",
  "format": "music",
  "type": "album",
  "album": "1223592280"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Album Request" %}
```
{
  "title": "DAMN",
  "format": "music",
  "type": "album"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Song Request" %}
```
{
  "title": "In My Feelings",
  "format": "music",
  "type": "song"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Song-in-Album Request" %}
```
{
  "title": "DAMN",
  "format": "music",
  "type": "song-in-album",
  "album": "1223592280"
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Here's how it will respond:

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Song Response" %}
```
{
    "issued": {
        "month": "6",
        "year": "2018",
        "day": "29"
    },
    "id": "SET",
    "author": [{
        "given": "Drake"
    }],
    "composer": [],
    "editor": [],
    "edition": null,
    "language": null,
    "title": "In My Feelings",
    "title-short": null,
    "publisher": null,
    "publisher-place": null,
    "source": null,
    "URL": null,
    "abstract": null,
    "collection-title": "Scorpion",
    "genre": "Hip-Hop/Rap",
    "type": "song"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="CSL-JSON Data Album Response" %}
```
{
    "issued": {
        "month": "4", "year":"2017", "day":"14"
    }
    ,
    "id":"SET",
    "author":[ {
        "given": "Kendrick", "family":"Lamar"
    }
    ],
    "composer":[],
    "editor":[],
    "edition":null,
    "language":null,
    "title":null,
    "title-short":null,
    "publisher":"Aftermath/Interscope (Top Dawg Entertainment)",
    "publisher-place":null,
    "source":null,
    "URL":null,
    "abstract":null,
    "collection-title":"DAMN.",
    "genre":"Hip-Hop/Rap",
    "type":"song"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Album Response" %}
```
{
    "resultCount": 49,
    "results": [{
            "wrapperType": "collection",
            "collectionType": "Album",
            "artistId": 368183298,
            "collectionId": 1223592280,
            "amgArtistId": 2412704,
            "artistName": "Kendrick Lamar",
            "collectionName": "DAMN.",
            "collectionCensoredName": "DAMN.",
            "artistViewUrl": "https://itunes.apple.com/us/artist/kendrick-lamar/368183298?uo=4",
            "collectionViewUrl": "https://itunes.apple.com/us/album/damn/1223592280?uo=4",
            "artworkUrl60": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/60x60bb.jpg",
            "artworkUrl100": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/100x100bb.jpg",
            "collectionPrice": 9.99,
            "collectionExplicitness": "explicit",
            "contentAdvisoryRating": "Explicit",
            "trackCount": 15,
            "copyright": "℗ 2017 Aftermath/Interscope (Top Dawg Entertainment)",
            "country": "USA",
            "currency": "USD",
            "releaseDate": "2017-04-14T07:00:00Z",
            "primaryGenreName": "Hip-Hop/Rap"
        },
        {
            "wrapperType": "collection",
            "collectionType": "Album",
            "artistId": 368183298,
            "collectionId": 1223585496,
            "amgArtistId": 2412704,
            "artistName": "Kendrick Lamar",
            "collectionName": "DAMN.",
            "collectionCensoredName": "DAMN.",
            "artistViewUrl": "https://itunes.apple.com/us/artist/kendrick-lamar/368183298?uo=4",
            "collectionViewUrl": "https://itunes.apple.com/us/album/damn/1223585496?uo=4",
            "artworkUrl60": "https://is3-ssl.mzstatic.com/image/thumb/Music82/v4/85/d4/c7/85d4c795-5a00-a3dd-fef5-36dd996dd6ec/source/60x60bb.jpg",
            "artworkUrl100": "https://is3-ssl.mzstatic.com/image/thumb/Music82/v4/85/d4/c7/85d4c795-5a00-a3dd-fef5-36dd996dd6ec/source/100x100bb.jpg",
            "collectionPrice": 9.99,
            "collectionExplicitness": "cleaned",
            "contentAdvisoryRating": "Clean",
            "trackCount": 15,
            "copyright": "℗ 2017 Aftermath/Interscope (Top Dawg Entertainment)",
            "country": "USA",
            "currency": "USD",
            "releaseDate": "2017-04-14T07:00:00Z",
            "primaryGenreName": "Hip-Hop/Rap"
        }, (...)
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Song Response" %}
```
{
    "resultCount": 50,
    "results": [{
            "wrapperType": "track",
            "kind": "song",
            "artistId": 271256,
            "collectionId": 1418213110,
            "trackId": 1418213402,
            "artistName": "Drake",
            "collectionName": "Scorpion",
            "trackName": "In My Feelings",
            "collectionCensoredName": "Scorpion",
            "trackCensoredName": "In My Feelings",
            "artistViewUrl": "https://itunes.apple.com/us/artist/drake/271256?uo=4",
            "collectionViewUrl": "https://itunes.apple.com/us/album/in-my-feelings/1418213110?i=1418213402&uo=4",
            "trackViewUrl": "https://itunes.apple.com/us/album/in-my-feelings/1418213110?i=1418213402&uo=4",
            "previewUrl": "https://audio-ssl.itunes.apple.com/apple-assets-us-std-000001/AudioPreview128/v4/dc/54/ba/dc54bad9-9c1b-e6d6-a91d-b09126664b34/mzaf_5589493968026216281.plus.aac.p.m4a",
            "artworkUrl30": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/4a/92/c4/4a92c451-466f-c94b-ee1f-a91dd2b5a978/source/30x30bb.jpg",
            "artworkUrl60": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/4a/92/c4/4a92c451-466f-c94b-ee1f-a91dd2b5a978/source/60x60bb.jpg",
            "artworkUrl100": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/4a/92/c4/4a92c451-466f-c94b-ee1f-a91dd2b5a978/source/100x100bb.jpg",
            "collectionPrice": 13.99,
            "trackPrice": 1.29,
            "releaseDate": "2018-06-29T07:00:00Z",
            "collectionExplicitness": "explicit",
            "trackExplicitness": "explicit",
            "discCount": 2,
            "discNumber": 2,
            "trackCount": 13,
            "trackNumber": 9,
            "trackTimeMillis": 217933,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Hip-Hop/Rap",
            "contentAdvisoryRating": "Explicit",
            "isStreamable": true
        },
        {
            "wrapperType": "track",
            "kind": "song",
            "artistId": 271256,
            "collectionId": 1406109769,
            "trackId": 1406109901,
            "artistName": "Drake",
            "collectionName": "Scorpion",
            "trackName": "In My Feelings",
            "collectionCensoredName": "Scorpion",
            "trackCensoredName": "In My Feelings",
            "artistViewUrl": "https://itunes.apple.com/us/artist/drake/271256?uo=4",
            "collectionViewUrl": "https://itunes.apple.com/us/album/in-my-feelings/1406109769?i=1406109901&uo=4",
            "trackViewUrl": "https://itunes.apple.com/us/album/in-my-feelings/1406109769?i=1406109901&uo=4",
            "previewUrl": "https://audio-ssl.itunes.apple.com/apple-assets-us-std-000001/AudioPreview128/v4/fa/4b/9e/fa4b9ea2-99c3-ab71-1103-68661ef7b6f3/mzaf_7196473382879067455.plus.aac.p.m4a",
            "artworkUrl30": "https://is4-ssl.mzstatic.com/image/thumb/Music115/v4/a7/ff/8d/a7ff8d0a-ecd3-d83c-16b1-398ac849f395/source/30x30bb.jpg",
            "artworkUrl60": "https://is4-ssl.mzstatic.com/image/thumb/Music115/v4/a7/ff/8d/a7ff8d0a-ecd3-d83c-16b1-398ac849f395/source/60x60bb.jpg",
            "artworkUrl100": "https://is4-ssl.mzstatic.com/image/thumb/Music115/v4/a7/ff/8d/a7ff8d0a-ecd3-d83c-16b1-398ac849f395/source/100x100bb.jpg",
            "collectionPrice": 13.99,
            "trackPrice": 1.29,
            "releaseDate": "2018-06-29T07:00:00Z",
            "collectionExplicitness": "cleaned",
            "trackExplicitness": "cleaned",
            "discCount": 2,
            "discNumber": 2,
            "trackCount": 13,
            "trackNumber": 9,
            "trackTimeMillis": 217925,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Hip-Hop/Rap",
            "contentAdvisoryRating": "Clean",
            "isStreamable": true
        }, (...)
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Song-in-Album Response" %}
```
{
    "resultCount": 15,
    "results": [{
                "wrapperType": "collection",
                "collectionType": "Album",
                "artistId": 368183298,
                "collectionId": 1223592280,
                "amgArtistId": 2412704,
                "artistName": "Kendrick Lamar",
                "collectionName": "DAMN.",
                "collectionCensoredName": "DAMN.",
                "artistViewUrl": "https://itunes.apple.com/us/artist/kendrick-lamar/368183298?uo=4",
                "collectionViewUrl": "https://itunes.apple.com/us/album/damn/1223592280?uo=4",
                "artworkUrl60": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/60x60bb.jpg",
                "artworkUrl100": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/100x100bb.jpg",
                "collectionPrice": 9.99,
                "collectionExplicitness": "explicit",
                "contentAdvisoryRating": "Explicit",
                "trackCount": 15,
                "copyright": "℗ 2017 Aftermath/Interscope (Top Dawg Entertainment)",
                "country": "USA",
                "currency": "USD",
                "releaseDate": "2017-04-14T07:00:00Z",
                "primaryGenreName": "Hip-Hop/Rap"
            },
            {
                "wrapperType": "track",
                "kind": "song",
                "artistId": 368183298,
                "collectionId": 1223592280,
                "trackId": 1223592491,
                "artistName": "Kendrick Lamar",
                "collectionName": "DAMN.",
                "trackName": "BLOOD.",
                "collectionCensoredName": "DAMN.",
                "trackCensoredName": "BLOOD.",
                "artistViewUrl": "https://itunes.apple.com/us/artist/kendrick-lamar/368183298?uo=4",
                "collectionViewUrl": "https://itunes.apple.com/us/album/blood/1223592280?i=1223592491&uo=4",
                "trackViewUrl": "https://itunes.apple.com/us/album/blood/1223592280?i=1223592491&uo=4",
                "previewUrl": "https://audio-ssl.itunes.apple.com/apple-assets-us-std-000001/AudioPreview122/v4/89/68/13/89681310-538a-06e3-36ae-7081e6f2cf0f/mzaf_4908141583770766017.plus.aac.p.m4a",
                "artworkUrl30": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/30x30bb.jpg",
                "artworkUrl60": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/60x60bb.jpg",
                "artworkUrl100": "https://is4-ssl.mzstatic.com/image/thumb/Music111/v4/56/46/3f/56463f62-0d8d-3595-368b-38a995f10e36/source/100x100bb.jpg",
                "collectionPrice": 9.99,
                "trackPrice": 1.29,
                "releaseDate": "2017-04-14T07:00:00Z",
                "collectionExplicitness": "explicit",
                "trackExplicitness": "explicit",
                "discCount": 1,
                "discNumber": 1,
                "trackCount": 14,
                "trackNumber": 1,
                "trackTimeMillis": 118067,
                "country": "USA",
                "currency": "USD",
                "primaryGenreName": "Hip-Hop/Rap",
                "contentAdvisoryRating": "Explicit",
                "isStreamable": true
            }, (...)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Podcast

Autofill requires the following fields to be sent in the body of the POST request. 

Autofill currently does not parse the feed url provided to provide specific information about podcast episodes in the CSL Data format.

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Podcast Request" %}
```
{
  "title": "Stuff You Should Know",
  "format": "podcast",
  "type": "podcast",
  "podcast": "278981407"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="CSL-JSON Data Episode Request" %}
```

```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Podcast Request" %}
```text
{
  "title": "Stuff You Should Know",
  "format": "podcast",
  "type": "podcast"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Episode Request" %}
```
{
  "title": "Stuff You Should Know",
  "format": "podcast",
  "type": "episode"
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Here's how it will respond:

{% code-tabs %}
{% code-tabs-item title="CSL-JSON Data Podcast Response" %}
```
{
    "issued": {
        "month": "7",
        "year": "2018",
        "day": "31"
    },
    "id": "SET",
    "author": [{
        "given": "HowStuffWorks"
    }],
    "composer": [],
    "editor": [],
    "edition": null,
    "language": null,
    "title": "Stuff You Should Know",
    "title-short": null,
    "publisher": null,
    "publisher-place": null,
    "source": null,
    "URL": null,
    "abstract": null,
    "collection-title": "Stuff You Should Know",
    "genre": "Society & Culture",
    "type": "song"
}
```
{% endcode-tabs-item %}

{% code-tabs-item title="CSL-JSON Data Episode Response" %}
```

```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Podcast Response" %}
```
{
    "resultCount": 5,
    "results": [{
            "wrapperType": "track",
            "kind": "podcast",
            "artistId": 284341002,
            "collectionId": 278981407,
            "trackId": 278981407,
            "artistName": "HowStuffWorks",
            "collectionName": "Stuff You Should Know",
            "trackName": "Stuff You Should Know",
            "collectionCensoredName": "Stuff You Should Know",
            "trackCensoredName": "Stuff You Should Know",
            "artistViewUrl": "https://itunes.apple.com/us/artist/howstuffworks/284341002?mt=2&uo=4",
            "collectionViewUrl": "https://itunes.apple.com/us/podcast/stuff-you-should-know/id278981407?mt=2&uo=4",
            "feedUrl": "https://feeds.megaphone.fm/stuffyoushouldknow",
            "trackViewUrl": "https://itunes.apple.com/us/podcast/stuff-you-should-know/id278981407?mt=2&uo=4",
            "artworkUrl30": "https://is4-ssl.mzstatic.com/image/thumb/Music128/v4/39/31/02/39310237-1c6c-4e43-7b2e-f561428a4dbe/source/30x30bb.jpg",
            "artworkUrl60": "https://is4-ssl.mzstatic.com/image/thumb/Music128/v4/39/31/02/39310237-1c6c-4e43-7b2e-f561428a4dbe/source/60x60bb.jpg",
            "artworkUrl100": "https://is4-ssl.mzstatic.com/image/thumb/Music128/v4/39/31/02/39310237-1c6c-4e43-7b2e-f561428a4dbe/source/100x100bb.jpg",
            "collectionPrice": 0.00,
            "trackPrice": 0.00,
            "trackRentalPrice": 0,
            "collectionHdPrice": 0,
            "trackHdPrice": 0,
            "trackHdRentalPrice": 0,
            "releaseDate": "2018-07-31T13:14:00Z",
            "collectionExplicitness": "cleaned",
            "trackExplicitness": "cleaned",
            "trackCount": 300,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Society & Culture",
            "contentAdvisoryRating": "Clean",
            "artworkUrl600": "https://is4-ssl.mzstatic.com/image/thumb/Music128/v4/39/31/02/39310237-1c6c-4e43-7b2e-f561428a4dbe/source/600x600bb.jpg",
            "genreIds": ["1324", "26"],
            "genres": ["Society & Culture", "Podcasts"]
        },
        {
            "wrapperType": "track",
            "kind": "podcast",
            "collectionId": 736826307,
            "trackId": 736826307,
            "artistName": "Andrew Fiebert, Thomas Frank | Talking about stuff you should know on investing, business building, and real estate like: Planet Money, Freakonomics Radio, Dave Ramsey, Tim Ferriss, Reply All, Radiolab, Side Hustle School, Joe Rogan, Fresh Air, Startup",
            "collectionName": "Listen Money Matters - Free your inner financial badass. This is not your father's boring personal finance show.",
            "trackName": "Listen Money Matters - Free your inner financial badass. This is not your father's boring personal finance show.",
            "collectionCensoredName": "Listen Money Matters - Free your inner financial badass. This is not your father's boring personal finance show.",
            "trackCensoredName": "Listen Money Matters - Free your inner financial badass. This is not your father's boring personal finance show.",
            "collectionViewUrl": "https://itunes.apple.com/us/podcast/listen-money-matters-free-your-inner-financial-badass/id736826307?mt=2&uo=4",
            "feedUrl": "http://www.listenmoneymatters.com/feed/podcast/",
            "trackViewUrl": "https://itunes.apple.com/us/podcast/listen-money-matters-free-your-inner-financial-badass/id736826307?mt=2&uo=4",
            "artworkUrl30": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/52/c9/2e/52c92e71-9a69-bc5c-de8d-5ac3b540ab92/source/30x30bb.jpg",
            "artworkUrl60": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/52/c9/2e/52c92e71-9a69-bc5c-de8d-5ac3b540ab92/source/60x60bb.jpg",
            "artworkUrl100": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/52/c9/2e/52c92e71-9a69-bc5c-de8d-5ac3b540ab92/source/100x100bb.jpg",
            "collectionPrice": 0.00,
            "trackPrice": 0.00,
            "trackRentalPrice": 0,
            "collectionHdPrice": 0,
            "trackHdPrice": 0,
            "trackHdRentalPrice": 0,
            "releaseDate": "2018-07-30T13:22:00Z",
            "collectionExplicitness": "explicit",
            "trackExplicitness": "explicit",
            "trackCount": 300,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Investing",
            "contentAdvisoryRating": "Explicit",
            "artworkUrl600": "https://is2-ssl.mzstatic.com/image/thumb/Music118/v4/52/c9/2e/52c92e71-9a69-bc5c-de8d-5ac3b540ab92/source/600x600bb.jpg",
            "genreIds": ["1412", "26", "1321", "1318", "1304", "1480"],
            "genres": ["Investing", "Podcasts", "Business", "Technology", "Education", "Software How-To"]
        },
        {
            "wrapperType": "track",
            "kind": "podcast",
            "collectionId": 412678859,
            "trackId": 412678859,
            "artistName": "J. 10 Initiative",
            "collectionName": "Catholic Stuff You Should Know",
            "trackName": "Catholic Stuff You Should Know",
            "collectionCensoredName": "Catholic Stuff You Should Know",
            "trackCensoredName": "Catholic Stuff You Should Know",
            "collectionViewUrl": "https://itunes.apple.com/us/podcast/catholic-stuff-you-should-know/id412678859?mt=2&uo=4",
            "feedUrl": "https://pinecast.com/feed/catholicstuff",
            "trackViewUrl": "https://itunes.apple.com/us/podcast/catholic-stuff-you-should-know/id412678859?mt=2&uo=4",
            "artworkUrl30": "https://is3-ssl.mzstatic.com/image/thumb/Music118/v4/8a/36/58/8a365812-a395-458f-7ba0-dfb7b7749169/source/30x30bb.jpg",
            "artworkUrl60": "https://is3-ssl.mzstatic.com/image/thumb/Music118/v4/8a/36/58/8a365812-a395-458f-7ba0-dfb7b7749169/source/60x60bb.jpg",
            "artworkUrl100": "https://is3-ssl.mzstatic.com/image/thumb/Music118/v4/8a/36/58/8a365812-a395-458f-7ba0-dfb7b7749169/source/100x100bb.jpg",
            "collectionPrice": 0.00,
            "trackPrice": 0.00,
            "trackRentalPrice": 0,
            "collectionHdPrice": 0,
            "trackHdPrice": 0,
            "trackHdRentalPrice": 0,
            "releaseDate": "2018-07-26T06:01:00Z",
            "collectionExplicitness": "cleaned",
            "trackExplicitness": "cleaned",
            "trackCount": 300,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Christianity",
            "contentAdvisoryRating": "Clean",
            "artworkUrl600": "https://is3-ssl.mzstatic.com/image/thumb/Music118/v4/8a/36/58/8a365812-a395-458f-7ba0-dfb7b7749169/source/600x600bb.jpg",
            "genreIds": ["1439", "26", "1314"],
            "genres": ["Christianity", "Podcasts", "Religion & Spirituality"]
        },
        {
            "wrapperType": "track",
            "kind": "podcast",
            "collectionId": 1305381419,
            "trackId": 1305381419,
            "artistName": "A.J. Hanenburg, Graeme Donaldson, and Thomas Magbee",
            "collectionName": "Classical Stuff You Should Know",
            "trackName": "Classical Stuff You Should Know",
            "collectionCensoredName": "Classical Stuff You Should Know",
            "trackCensoredName": "Classical Stuff You Should Know",
            "collectionViewUrl": "https://itunes.apple.com/us/podcast/classical-stuff-you-should-know/id1305381419?mt=2&uo=4",
            "feedUrl": "https://www.classicalstuff.net/episodes-1/?format=rss",
            "trackViewUrl": "https://itunes.apple.com/us/podcast/classical-stuff-you-should-know/id1305381419?mt=2&uo=4",
            "artworkUrl30": "https://is3-ssl.mzstatic.com/image/thumb/Music128/v4/5f/e1/12/5fe112ed-c22d-49fe-c0c4-37e0e25ca96d/source/30x30bb.jpg",
            "artworkUrl60": "https://is3-ssl.mzstatic.com/image/thumb/Music128/v4/5f/e1/12/5fe112ed-c22d-49fe-c0c4-37e0e25ca96d/source/60x60bb.jpg",
            "artworkUrl100": "https://is3-ssl.mzstatic.com/image/thumb/Music128/v4/5f/e1/12/5fe112ed-c22d-49fe-c0c4-37e0e25ca96d/source/100x100bb.jpg",
            "collectionPrice": 0.00,
            "trackPrice": 0.00,
            "trackRentalPrice": 0,
            "collectionHdPrice": 0,
            "trackHdPrice": 0,
            "trackHdRentalPrice": 0,
            "releaseDate": "2018-07-31T14:01:00Z",
            "collectionExplicitness": "cleaned",
            "trackExplicitness": "cleaned",
            "trackCount": 48,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Literature",
            "contentAdvisoryRating": "Clean",
            "artworkUrl600": "https://is3-ssl.mzstatic.com/image/thumb/Music128/v4/5f/e1/12/5fe112ed-c22d-49fe-c0c4-37e0e25ca96d/source/600x600bb.jpg",
            "genreIds": ["1401", "26", "1301", "1314", "1439", "1304", "1415"],
            "genres": ["Literature", "Podcasts", "Arts", "Religion & Spirituality", "Christianity", "Education", "K-12"]
        },
        {
            "wrapperType": "track",
            "kind": "podcast",
            "collectionId": 1055726073,
            "trackId": 1055726073,
            "artistName": "Scouting Stuff Team",
            "collectionName": "Scouting Stuff You Should Know",
            "trackName": "Scouting Stuff You Should Know",
            "collectionCensoredName": "Scouting Stuff You Should Know",
            "trackCensoredName": "Scouting Stuff You Should Know",
            "collectionViewUrl": "https://itunes.apple.com/us/podcast/scouting-stuff-you-should-know/id1055726073?mt=2&uo=4",
            "feedUrl": "http://scoutingstuffpodcast.com/feed.xml",
            "trackViewUrl": "https://itunes.apple.com/us/podcast/scouting-stuff-you-should-know/id1055726073?mt=2&uo=4",
            "artworkUrl30": "https://is1-ssl.mzstatic.com/image/thumb/Music127/v4/29/a1/00/29a100d1-549a-5542-6f31-5f01ad50d9cb/source/30x30bb.jpg",
            "artworkUrl60": "https://is1-ssl.mzstatic.com/image/thumb/Music127/v4/29/a1/00/29a100d1-549a-5542-6f31-5f01ad50d9cb/source/60x60bb.jpg",
            "artworkUrl100": "https://is1-ssl.mzstatic.com/image/thumb/Music127/v4/29/a1/00/29a100d1-549a-5542-6f31-5f01ad50d9cb/source/100x100bb.jpg",
            "collectionPrice": 0.00,
            "trackPrice": 0.00,
            "trackRentalPrice": 0,
            "collectionHdPrice": 0,
            "trackHdPrice": 0,
            "trackHdRentalPrice": 0,
            "releaseDate": "2018-07-31T14:57:00Z",
            "collectionExplicitness": "cleaned",
            "trackExplicitness": "cleaned",
            "trackCount": 110,
            "country": "USA",
            "currency": "USD",
            "primaryGenreName": "Non-Profit",
            "contentAdvisoryRating": "Clean",
            "artworkUrl600": "https://is1-ssl.mzstatic.com/image/thumb/Music127/v4/29/a1/00/29a100d1-549a-5542-6f31-5f01ad50d9cb/source/600x600bb.jpg",
            "genreIds": ["1476", "26", "1325"],
            "genres": ["Non-Profit", "Podcasts", "Government & Organizations"]
        }
    ]
}

```
{% endcode-tabs-item %}

{% code-tabs-item title="Search Episode Response" %}
```

```
{% endcode-tabs-item %}
{% endcode-tabs %}

## TV Show {#podcast}

TV Shows are not currently supported by autofill. We expect to add support for this soon.

## Journal

Journals are not currently supported by autofill. We expect to add support for this soon.

## Digital Image

Digital images are not currently supported by autofill. We expect to add support for this soon.

## Other Formats

[Definitions by Zotero](https://www.zotero.org/support/kb/item_types_and_fields). Formats marked in bold are supported by CloudCite's Autofill API.

| Item Type | Description |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Artwork | A piece of artwork \(e.g., an oil painting, photograph, or sculpture\). Also use this item type for other types of images or visual items \(e.g., scientific figures\). |
| **Audio Recording** | Any form of audio recording, including music, spoken word, sound effects, archival recordings, or audio-based scientific figures. |
| Bill | A proposed piece of legislation. |
| Blog Post | An article or entry posted to a personal blog website. For online articles published as part of a larger online publication \(e.g., [NYT Blogs](http://www.nytimes.com/interactive/blogs/directory.html)\), using `Magazine Article` or `Newspaper Article` generally yields better results. |
| **Book** | A book or similar published item. For government documents, technical reports, manuals, etc., use `Report`instead. This item type can also be adapted to fit many types of unusual items. |
| Book Section | A section of a book. Usually chapters, but also forewords, prefaces, introductions, appendices, afterwords, comments, etc. |
| Case | A legal case, either published or unpublished. |
| Computer Program | A piece of software or other computer program. |
| Conference Paper | A paper presented at a conference and subsequently published in a formal conference proceedings publication \(e.g., as a book, report, or issue of a journal\). For conference papers that have not been published in a proceedings, use `Presentation`. |
| Dictionary Entry | An entry published as part of a dictionary. |
| Document | A generic document item. This item type has a poor selection of fields and poor support in citation styles, so it should generally be avoided. |
| Email | A message sent via email. This type could also be used for other forms of personal communication. |
| Encyclopedia Article | An article or chapter published as part of an encyclopedia. |
| **Film** | A film or motion picture. Generally, use this type for artistically-oriented films \(including fictional, non-fictional, and documentary films\). For other types of video items, use `Video Recording`. |
| Forum Post | A post on an online discussion forum. Also use this type for items such as Facebook posts or tweets. |
| Hearing | A formal hearing or meeting report by a legislative body. |
| Instant Message | A message sent via an instant message or chat service. This type could also be used for other forms of personal communication. |
| Interview | An interview with a person, including recordings, transcripts, or other records of the interview. |
| Journal Article | An article published in a scholarly journal \(either print or online\). |
| Letter | A letter sent between persons or organizations. This type could also be used for other forms of personal communication. |
| Magazine Article | An article published in a non-scholarly, popular, or trade magazine \(either print or online\). |
| Manuscript | An unpublished manuscript. Use this type for both historical documents and modern unpublished work \(e.g., unpublished manuscripts, manuscripts submitted for publication, working papers that are not widely available\). Can also be used for other forms of historical or archival documents. This item type can also be adapted to fit many types of unusual items. |
| Map | A map. Also use this type for geographic models. |
| Newspaper Article | An article published in a newspaper \(either print or online\). |
| Patent | A patent awarded for an invention. |
| **Podcast** | A [podcast](https://en.wikipedia.org/wiki/Podcast) \(an episode of an audio or video program distributed online, often via subscription\). |
| Presentation | A presentation made as part of a conference, meeting, symposium, lecture, etc. This item type refers to the presentation itself, not a written version published as part of a conference proceedings \(use `Conference Paper` for such published versions\). |
| Radio Broadcast | An audio broadcast, such as a radio news show, an episode of a radio entertainment series, or similar. Includes broadcasts from online radio stations and audio broadcasts archived online \(cf. `Podcast`\). |
| Report | A report published by an organization, institution, government department, or similar entity. Also used for working papers and preprints distributed through institutional repositories or preprint servers. This item type can also be adapted to fit many types of unusual items. |
| Statute | A law or other piece of enacted legislation. |
| Thesis | A thesis submitted as part of a student applying for a degree \(either published or unpublished\). |
| **TV Broadcast** | An episode of a television series. |
| Video Recording | A video recording. Use this type for general video items that do not fit into one of the more specific video item types \(e.g., Film, TV Broadcast\), such as YouTube videos or video-based scientific figures. |
| **Webpage** | An online page of a website. When possible, use one of the more specific item types above \(e.g., Magazine Article, Blog Post, Report\). |
| Note | A standalone note. |
| Attachment | A standalone attachment file \(e.g., a PDF, JPEG, DOCX, PPTX, XLSX, or ODT file\). |

