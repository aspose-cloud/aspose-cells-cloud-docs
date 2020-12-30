---
title: "Update Chart Legend in a Worksheet"
type: docs
url: /update-chart-legend-in-a-worksheet/
weight: 90
---

## **Introduction**
This example shows how to update a chart legend of a chart using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/charts/{chartIndex}/legend|POST|Updates chart legend in worksheet|[PostWorksheetChartLegend](https://apireference.aspose.cloud/cells/#/Charts/PostWorksheetChartLegend)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST  "http://api.aspose.com/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet5/charts/0/legend" -d '{"Font":{"Color":{"A":"1", "R":"255", "G":"0", "B":"0"}, "DoubleSize":10.0, "IsBold":true, "IsItalic":false, "IsStrikeout":false, "IsSubscript":false, "IsSuperscript":false, "Name":"Arial", "Size":15, "Underline":"None"}, "Shadow":true}' -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Legend": {

    "Position": "Right",

    "LegendEntries": {

      "link": {

        "Href": "/legendEntries",

        "Rel": "self"

      }

    },

    "Area": {

      "BackgroundColor": {

        "A": "0",

        "R": "0",

        "G": "0",

        "B": "0"

      },

      "FillFormat": {

        "Type": "Automatic"

      },

      "ForegroundColor": {

        "A": "0",

        "R": "0",

        "G": "0",

        "B": "0"

      },

      "Formatting": "Automatic",

      "InvertIfNegative": false,

      "Transparency": 0.0

    },

    "AutoScaleFont": false,

    "BackgroundMode": "Automatic",

    "Border": {

      "BeginArrowLength": "Medium",

      "BeginArrowWidth": "Medium",

      "BeginType": "None",

      "CapType": "Flat",

      "Color": {

        "A": "0",

        "R": "0",

        "G": "0",

        "B": "0"

      },

      "CompoundType": "Single",

      "DashType": "Solid",

      "EndArrowLength": "Medium",

      "EndArrowWidth": "Medium",

      "EndType": "None",

      "IsAuto": false,

      "IsAutomaticColor": false,

      "IsVisible": false,

      "JoinType": "Round",

      "Style": "Solid",

      "Transparency": 0.0,

      "Weight": "HairLine",

      "WeightPt": 0.0

    },

    "Font": {

      "Color": {

        "A": "0",

        "R": "255",

        "G": "0",

        "B": "0"

      },

      "DoubleSize": 15.0,

      "IsBold": false,

      "IsItalic": false,

      "IsStrikeout": false,

      "IsSubscript": false,

      "IsSuperscript": false,

      "Name": "Arial",

      "Size": 15,

      "Underline": "None"

    },

    "IsAutomaticSize": false,

    "Shadow": false,

    "Width": 823,

    "Height": 1043,

    "X": 3125,

    "Y": 1466,

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet5/charts/0/legend",

      "Rel": "self"

    }

  },

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

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Charts-UpdateChartLegend-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-chart-UpdateChartLegend-update-chart-legend.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Charts-PostWorksheetChartLegend-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Charts-update_chart_legend-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Charts-UpdateChartLegend-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "UpdateChartLegendInWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-chart-UpdateChartLegend-update-chart-legend.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Charts-UpdateChartLegend-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "74fffa317bc5ba65dc6536005e5bb683" >}}

{{< /tab >}}

{{< /tabs >}}
