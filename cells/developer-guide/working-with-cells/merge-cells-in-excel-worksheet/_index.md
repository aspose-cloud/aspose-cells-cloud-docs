---
title: "Merge Cells in Excel Worksheet"
type: docs
url: /merge-cells-in-excel-worksheet/
weight: 110
---

## **Introduction**
This example shows how to merge rows in an Excel Worksheet using Aspose.Cells Cloud API.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|` `/cells/{name}/worksheets/{sheetName}/cells/merge|` `POST|` `Merge cells in a Worksheet|` `[PostWorksheetMerge](https://apireference.aspose.cloud/cells/#/Cells/PostWorksheetMerge)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/cells/merge?startRow=10&startColumn=10&totalRows=10&totalColumns=10" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1Njk3ODcxODksImV4cCI6MTU2OTg3MzU4OSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.mF1ctCv6x3Kszw2Izt6q4CwBg5vmeGvfHc-yjuYFh5f61jJckNpaJTLS0cpeKx7PUfKsEtdKt-UdhqKT9BJdmVGG305D7P7NGFs7fU3T0GXDFjxh0dzMRbbmhGQC9wHoa5PlV-BZ9xoNk-utW\_FqMP\_0GJ9zTgXBAFcE2uA8LD\_CyiGMLDCvOgPc614jHUqREfk2oJD0rPc6rrZiv3XL-zJUncUIyXxbNRJvIImcukC7w7TJfZQ3\_fPnw-xvjFwY3Bc8VfMdBZhmyFpiRH6\_7oinsP11FD8fPSUb5ph4M8x5XL1bgGLp54RUguMzzbj\_\_MgdT4dte8lGe8UkTN5Qyw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Python" tabName5="Node.js" tabName6="Android" tabName7="Objective C" tabName8="Perl" tabName9="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Cells-MergeCellsWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Cells-PostWorksheetMerge-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-merge\_cells-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "MergeCellsInExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Cells-MergeCellsWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-cells-MergeCellsWorksheet-merge-cells-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Cells-MergeCellsWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "43d141d338376958100f323ea790f350" >}}

{{< /tab >}}

{{< /tabs >}}
