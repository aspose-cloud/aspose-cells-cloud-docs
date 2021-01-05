---
title: "Set Chart Title in Excel Worksheet"
type: docs
url: /set-chart-title-in-excel-worksheet/
weight: 130
---

## **Introduction**
This example shows how to add title to a chart using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/charts/{chartIndex}/title|PUT|Set chart title|[PutWorksheetChartTitle](https://apireference.aspose.cloud/cells/#/Charts/PutWorksheetChartTitle)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "http://api.aspose.com/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet5/charts/0/title" -d '{"Text":"Sales Chart"}' -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Title": {

    "IsVisible": false,

    "RotationAngle": 0,

    "Text": "Sales Chart",

    "TextDirection": "Context",

    "TextHorizontalAlignment": "Center",

    "TextVerticalAlignment": "Center",

    "Area": {

      "BackgroundColor": {

        "A": "0",

        "R": "0",

        "G": "0",

        "B": "0"

      },

      "FillFormat": {

        "Type": "None"

      },

      "ForegroundColor": {

        "A": "0",

        "R": "0",

        "G": "0",

        "B": "0"

      },

      "Formatting": "None",

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

        "A": "255",

        "R": "0",

        "G": "0",

        "B": "0"

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

    "IsAutomaticSize": false,

    "IsInnerMode": false,

    "Shadow": false,

    "Width": 994,

    "Height": 575,

    "X": 1497,

    "Y": 125,

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet5/charts/0/title",

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
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Charts-SetChartTitle-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}



{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-chart-SetChartTitle-set-chart-title.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Charts-PutWorksheetChartTitle-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Charts-add_chart_title-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "SetChartTitle.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Charts-SetChartTitle-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-chart-SetChartTitle-set-chart-title.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Charts-SetChartTitle-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "728d523e11f8751f5f601bafb04ab86f" >}}

{{< /tab >}}

{{< /tabs >}}
