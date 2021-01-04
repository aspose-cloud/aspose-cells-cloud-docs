---
title: "Get Chart Legend from a Worksheet"
type: docs
url: /get-chart-legend-from-a-worksheet/
weight: 80
---

## **Introduction**
This example shows how to get information of a chart legend of a chart using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/charts/{chartIndex}/legend|GET|Gets chart legend description in worksheet|[GetWorksheetChartLegend](https://apireference.aspose.cloud/cells/#/Charts/GetWorksheetChartLegend)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "http://api.aspose.com/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet5/charts/0/legend" -H "Content-Type: application/json" -H "Accept: application/json"

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

        "Rel": "self",

        "Title": null,

        "Type": null

      }

    },

    "Area": {

      "BackgroundColor": {

        "A": 0,

        "R": 0,

        "G": 0,

        "B": 0

      },

      "FillFormat": {

        "Type": "Automatic",

        "SolidFill": null,

        "PatternFill": null,

        "TextureFill": null,

        "GradientFill": null,

        "ImageData": null

      },

      "ForegroundColor": {

        "A": 0,

        "R": 0,

        "G": 0,

        "B": 0

      },

      "Formatting": "Automatic",

      "InvertIfNegative": false,

      "Transparency": 0.0

    },

    "AutoScaleFont": true,

    "BackgroundMode": "Automatic",

    "Border": {

      "BeginArrowLength": "Medium",

      "BeginArrowWidth": "Medium",

      "BeginType": "None",

      "CapType": "Flat",

      "Color": {

        "A": 0,

        "R": 0,

        "G": 0,

        "B": 0

      },

      "CompoundType": "Single",

      "DashType": "Solid",

      "EndArrowLength": "Medium",

      "EndArrowWidth": "Medium",

      "EndType": "None",

      "GradientFill": null,

      "IsAuto": true,

      "IsAutomaticColor": true,

      "IsVisible": true,

      "JoinType": "Round",

      "Style": "Solid",

      "Transparency": 0.0,

      "Weight": "HairLine",

      "WeightPt": 0.0

    },

    "Font": {

      "Color": {

        "A": 255,

        "R": 0,

        "G": 0,

        "B": 0

      },

      "DoubleSize": 10.0,

      "IsBold": false,

      "IsItalic": false,

      "IsStrikeout": false,

      "IsSubscript": false,

      "IsSuperscript": false,

      "Name": "Arial",

      "Size": 10,

      "Underline": "None"

    },

    "IsAutomaticSize": true,

    "IsInnerMode": null,

    "Shadow": false,

    "ShapeProperties": null,

    "Width": 823,

    "Height": 1043,

    "X": 3125,

    "Y": 1466,

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet5/charts/0/legend",

      "Rel": "self",

      "Title": null,

      "Type": null

    }

  },

  "Code": 0,

  "Status": "0"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Charts-GetChartLegend-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-chart-GetChartLegend-get-chart-legend.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Charts-GetWorksheetChartLegend-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Charts-get_chart_legend-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "GetChartLegendFromWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Charts-GetChartLegend-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-chart-GetChartLegend-get-chart-legend.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Charts-GetChartLegend-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "76b8d73d934c0f03675299687805040f" >}}

{{< /tab >}}

{{< /tabs >}}
