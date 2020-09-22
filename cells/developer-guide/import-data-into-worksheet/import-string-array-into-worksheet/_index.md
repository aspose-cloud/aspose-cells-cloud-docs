---
title: "Import String Array into Worksheet"
type: docs
url: /import-string-array-into-worksheet/
weight: 40
---

## **Introduction**
This example shows how to import string array into worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/importdata|POST|Imports data into workbook|[PostImportData](https://apireference.aspose.cloud/cells/#/Workbook/PostImportData)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/importdata" -d '{"FirstRow":1,"FirstColumn":2,"IsVertical":true,"Data":null,"DestinationWorksheet":"Sheet1","IsInsert":true,"ImportDataType":"StringArray","Source":{"FileSourceType":1,"FilePath":"Array_string_json.txt"}}' -H "Content-Type: application/json" -H "Accept: application/json"

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
### **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-ImportData-PostImportDataCloudFile-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostImportDataCloudFile-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-post_import_data-.rb" >}}

{{< /tab >}}

{{< /tabs >}}




