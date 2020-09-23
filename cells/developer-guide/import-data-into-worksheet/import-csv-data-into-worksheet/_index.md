---
title: "Import CSV Data into Worksheet"
type: docs
url: /import-csv-data-into-worksheet/
weight: 50
---

## **Introduction**
This example shows how to import csv data into worksheet using Aspose.Cells for Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/importdata|POST|Imports data into workbook|[PostImportData](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/importdata" -d '{"SeparatorString":",", "ConvertNumericData":true, "FirstRow":1, "FirstColumn":2, "SourceFile":"TestImportDataCSV.csv", "DestinationWorksheet":"Sheet1", "IsInsert":true, "ImportDataType":"CSVData", "Source":null}' -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
