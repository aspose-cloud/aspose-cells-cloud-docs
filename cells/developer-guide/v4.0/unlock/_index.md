---
title: "Unlock"
second_title: "Aspose.Cells Cloud Document"
type: docs
url: /lite/unlock/
aliases: [/v4.0/unlock/]
keywords: "REST API, unlock, spreadsheets, excel,lite"
description: "Cells.Cloud API for Excel operate: unlock excel file to different format files."
weight: 50
---

This REST API `unlock` multipart excel files.

The request is an HTTP request with multipart content (see [RFC 2046](http://tools.ietf.org/html/rfc2046#page-17) or [RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). 

**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|password|string| |


**Request Body Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|datafile| file | The data files save into multipart content.|



## REST API

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/unlock|POST|Unlock multipart Excel files.|[PostUnlock](https://apireference.aspose.cloud/cells/#/unlock/PostUnlock)|


The [OpenAPI Specification]((https://apireference.aspose.cloud/cells/#/unlock/PostUnlock) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.


{{< tabs tabTotal="1" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

curl  -v "https://api.aspose.cloud/v4.0/cells/unlock?password=aspose" \
-X PUT \
-H "accept: multipart/form-data" \
-H "Content-Type: multipart/form-data"  \
-d {["my_file1.xlsx":{},"my_file2.xlsx":{}]}
```

{{< /tab >}}

{{< tab tabNum="2" >}}

```bash
{
"Files": [
        {
            "FileName": "my_file1.xlsx",
            "FileSize": 523672,
            "FileContent": "--Base64 encoded file content--"
        },
        {
            "FileName": "my_file2.xlsx",
            "FileSize": 523672,
            "FileContent": "--Base64 encoded file content--"
        }
    ]
}
```

{{< /tab >}}
{{< /tabs >}}

## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.

The following code examples demonstrate how to make calls to Aspose.Cells web services using various SDKs:



