---
title: "Merge"
second_title: "Aspose.Cells Cloud Document"
type: docs
url: /lite/merge/
aliases: [/v4.0/merge/]
keywords: "REST API, merge, spreadsheets, excel,lite"
description: "Cells.Cloud API for Excel operate: merge excel files to excel file."
weight: 20
---

This REST API `merge` multipart Excel files to an Excel file.

The request is an HTTP request with multipart content (see [RFC 2046](http://tools.ietf.org/html/rfc2046#page-17) or [RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). 

**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
| format |string| Merged file format. The default value is xlsx. |
| property name of SaveOptions inherited class |string| Set the property of kinds of save options value through query string.  |

- [SaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/saveoptions) inherited class page description :

    - [difsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/difsaveoptions) 
    - [docxsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) 
    - [imagesaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/imagesaveoptions) 
    - [htmlsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) 
    - [markdownsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) 
    - [odssaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/odssaveoptions) 
    - [ooxmlsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/ooxmlsaveoptions) 
    - [pdfsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) 
    - [pptxsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) 
    - [spreadsheetml2003saveoptions](https://apireference.aspose.com/cells/net/aspose.cells/spreadsheetml2003saveoptions) 
    - [svgsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/svgsaveoptions) 
    - [txtsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/txtsaveoptions) 
    - [xlsbsaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/xlsbsaveoptions) 
    - [xlssaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/xlssaveoptions) 
    - [xpssaveoptions](https://apireference.aspose.com/cells/net/aspose.cells/xpssaveoptions)



**Request Body Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|datafile| file | The data files save into multipart content.|


## REST API

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/merge|POST|Merge multipart Excel files to an Excel file.|[PostMerge](https://apireference.aspose.cloud/cells/#/merge/PostMerge)|


The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/merge/PostMerge) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.


{{< tabs tabTotal="1" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

curl -v "https://api.aspose.cloud/v4.0/cells/merge" \
-X PUT \
-H "accept: multipart/form-data" \
-H "Content-Type: multipart/form-data"  \
-d {"my_file1.xlsx":{},"my_file2.xlsx":{}}

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```bash
{
"FileName": "my_file.xlsx",
"FileSize": 523672,
"FileContent": "--Base64 encoded file content--"
}
```

{{< /tab >}}
{{< /tabs >}}

## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.

The following code examples demonstrate how to make calls to Aspose.Cells web services using various SDKs:



