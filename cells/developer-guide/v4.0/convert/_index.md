---
title: "Convert"
second_title: "Aspose.Cells Cloud Document"
type: docs
url: /lite/convert/
aliases: [/v4.0/convert/]
keywords: "REST API, convert, spreadsheets, excel,lite"
description: "Cells.Cloud API for Excel operate: convert excel file to different format file."
weight: 10
---


This REST API `convert` multipart Excel files to different format files.

The request is an HTTP request with multipart content (see [RFC 2046](http://tools.ietf.org/html/rfc2046#page-17) or [RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). 

**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
| format |string| file format(csv/xls/html/mhtml/ods/pdf/xml/txt/tiff/xlsb/xlsm/xlsx/xltm/xltx/xps/png/jpg/gif/emf/bmp/md/Numbers/wmf/svg) |
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
|/cells/convert|POST|Convert multipart Excel files to some format|[PostConvert](https://apireference.aspose.cloud/cells/#/convert/PutConvert)|


The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/convert/PutConvert) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.




{{< tabs tabTotal="1" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

curl -v "https://api.aspose.cloud/v4.0/cells/convert?format=pdf" 
-X PUT \
-H "accept: multipart/form-data" \
-H "Content-Type: multipart/form-data"  \
-d {["my_file1.xlsx":{}, "my_file2.xls":{}]}

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```bash
{
"Files": [
        {
            "FileName": "my_file1.pdf",
            "FileSize": 523672,
            "FileContent": "--Base64 encoded file content--"
        },
        {
            "FileName": "my_file2.pdf",
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



