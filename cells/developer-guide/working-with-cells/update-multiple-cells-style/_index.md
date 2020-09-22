---
title: "Update Multiple Cells Style"
type: docs
url: /update-multiple-cells-style/
weight: 20
---

## **Introduction**
This example shows how to update multiple cells style of Excel Worksheet using Aspose.Cells Cloud API.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/cells/style|POST|Updates cell's range style in worksheet|` `[PostUpdateWorksheetRangeStyle](https://apireference.aspose.cloud/cells/#/Cells/PostUpdateWorksheetRangeStyle)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/cells/style?range=a1%3Aa10" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Font\": { \"Color\": { \"A\":255, \"R\": 255, \"G\": 255, \"B\": 0 }, \"DoubleSize\": 10, \"IsBold\": true, \"IsItalic\": true, \"IsStrikeout\": true, \"IsSubscript\": true, \"IsSuperscript\": true, \"Name\": \"Arial\", \"Size\": 22 }, \"Name\": \"string\", \"CultureCustom\": \"string\", \"Custom\": \"string\", \"BackgroundColor\": { \"A\": 10, \"R\": 10, \"G\": 10, \"B\": 10 }, \"ForegroundColor\": { \"A\": 255, \"R\": 255, \"G\": 255, \"B\": 0 }

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
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="PHP" tabName2="Ruby" tabName3="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Cells-PostUpdateWorksheetCellStyle-.php" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Cells-post_update_worksheet_cell_style-.rb" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "59dae0a6697e3c68ade244ed28b27d10" >}}

{{< /tab >}}

{{< /tabs >}}
