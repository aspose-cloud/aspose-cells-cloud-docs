---
title: "Import CSV Data into Excel Worksheet"
type: docs
url: /import-csv-data-into-worksheet/
aliases: [/import-csv-data-into-excel-worksheet/]
description: "Cells.Cloud API for Excel operate: Import csv Data into Excel Worksheet."
weight: 50
---


This REST API import csv data into Excel work sheet.

The request is an HTTP request with multipart content (see [RFC 2046](http://tools.ietf.org/html/rfc2046#page-17) or [RFC 1341](http://www.w3.org/Protocols/rfc1341/7_2_Multipart.html)). The first part of the multipart content contains the ImportBatchDataOption data and the second contains a data file.

The important parameters are described in the following table:

**Query Parameter**

|Parameter Name|Type|Description|
| :- | :- | :- |
|folder|string|Original workbook folder.|
|storageName|string|Storage name.|

**Request Body Parameter**

|Parameter Name|Type|Description|
|ImportCSVDataOption|Object | import csv data option.The first part of the multipart content.|
|datafile|data file |If the file source type of data file is the request body, The data file save into the second part of the multipart content.|


**ImportCSVDataOption**

| Parameter Name|Type|Description|
| :- | :- | :- |
| SeparatorString | string |  |
| ConvertNumericData | string | true/false.|
| FirstRow | int | |
| FirstColumn | int | |
| SourceFile | string | |
| CustomParsers | List<CustomParserConfig> |  |


**CustomParserConfig**

| Parameter Name|Type|Description|
| :- | :- | :- |
| ColumnIndex | int |  | 
| ParseMethod | string |  | 
| CustomStyle | string |  |




## REST API


|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/importdata|POST|Imports data into workbook|[PostImportData](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData)|


The [OpenAPI Specification](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData) defines a publicly accessible programming interface and lets you carry out REST interactions directly from a web browser. 

You can use **cURL** command-line tool to access Aspose.Cells web services easily. The following example shows how to make calls to Cloud API with cURL.


{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```bash

curl -X POST "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/importdata" -d '{"SeparatorString":",", "ConvertNumericData":true, "FirstRow":1, "FirstColumn":2, "SourceFile":"TestImportDataCSV.csv", "DestinationWorksheet":"Sheet1", "IsInsert":true, "ImportDataType":"CSVData", "Source":null}' -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
## Cloud SDK Family

Using an SDK is the best way to speed up the development. An SDK takes care of low-level details and lets you focus on your project tasks. Please check out the [GitHub repository](https://github.com/aspose-cells-cloud) for a complete list of Aspose.Cells Cloud SDKs.

The following code examples demonstrate how to make calls to Aspose.Cells web services using various SDKs:

