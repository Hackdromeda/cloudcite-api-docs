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
{% code-tabs-item title="CSL-JSON Data for Website" %}
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

