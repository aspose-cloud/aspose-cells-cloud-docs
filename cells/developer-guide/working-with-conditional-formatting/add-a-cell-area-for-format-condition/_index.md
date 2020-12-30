---
title: "Add a Cell Area for Format Condition"
type: docs
url: /add-a-cell-area-for-format-condition/
weight: 30
---

## **Introduction**
This example shows how to add a cell area for format condition using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/conditionalFormattings/{index}/area|PUT|Adds a cell area for format condition|[PutWorksheetFormatConditionArea](https://apireference.aspose.cloud/cells/#/ConditionalFormattings/PutWorksheetFormatConditionArea)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet1/conditionalFormattings/0/area?cellArea=A1:C3" -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Code": "200",
  "Status": "OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Python" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}



{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNet-CSharp-ConditionalFormatting-FormatConditionArea-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-cells-add-cells-area-for-format-condition.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}



{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-ConditionalFormatting-put_worksheet_format_condition_area-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}



{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-ConditionalFormatting-FormatConditionArea-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}



{{< /tab >}}

{{< tab tabNum="7" >}}



{{< /tab >}}

{{< tab tabNum="8" >}}



{{< /tab >}}

{{< tab tabNum="9" >}}



{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-ConditionalFormatting-FormatConditionArea-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}



{{< gist "aspose-cloud" "597f99e44a3ac676ca8273b28f088ad2" >}}

{{< /tab >}}

{{< /tabs >}}
