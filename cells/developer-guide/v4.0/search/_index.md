---
title: "Search"
second_title: "Aspose.Cells Cloud Document"
type: docs
url: /lite/search/
aliases: [/v4.0/search/]
keywords: "REST API, search, spreadsheets, excel,lite"
description: "Cells.Cloud API for Excel operate: search text from excel files."
weight: 40
---

This REST API `search` text from multipart excel files.

The request is an HTTP request with multipart content (see [RFC 2046](http://tools.ietf.org/html/rfc2046#page-17) or [RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). 

**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|text|string| Search value. |

**Request Body Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|datafile| file | The data files save into multipart content.|



## REST API

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/search|POST|Search text from multipart Excel files.|[PostSearch](https://apireference.aspose.cloud/cells/#/search/PostSearch)|


The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/search/PostSearch) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.


{{< tabs tabTotal="1" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

curl -v "https://api.aspose.cloud/v4.0/cells/search?text=teststring" \
-X PUT \
-H "accept: multipart/form-data" \
-H "Content-Type: multipart/form-data" \
-d {"Book1.xlsx":{},"MyDoc.xlx":{}}

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```bash
[{
    "Text": "teststringsearch",
    "link": {
        "Href": "Book1.xlsx/worksheets/Sheet2",
        "Rel": "parent",
        "Title": null,
        "Type": null
    }
}]
```

{{< /tab >}}
{{< /tabs >}}

## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.

The following code examples demonstrate how to make calls to Aspose.Cells web services using various SDKs:



