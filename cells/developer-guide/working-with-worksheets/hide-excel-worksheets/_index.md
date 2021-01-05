---
title: "Hide Excel Worksheets"
type: docs
url: /hide-excel-worksheets/
weight: 50
---

## **Introduction**
This example shows how to hide a worksheet in a workbook using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/visible|PUT|Changes worksheet visibility|[PutChangeVisibilityWorksheet](https://apireference.aspose.cloud/cells/#/Worksheets/PutChangeVisibilityWorksheet)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "http://api.aspose.com/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1/visible?isVisible=false" -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Worksheet": {

    "Links": [

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1",

        "Rel": "self"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/tiff",

        "Title": "Download As TIFF"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/jpeg",

        "Title": "Download As Jpeg"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/png",

        "Title": "Download As Png"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/bmp",

        "Title": "Download As Bmp"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/gif",

        "Title": "Download As Gif"

      }

    ],

    "DisplayRightToLeft": false,

    "DisplayZeros": false,

    "FirstVisibleColumn": 0,

    "FirstVisibleRow": 0,

    "Name": "Sheet1",

    "Index": 0,

    "IsGridlinesVisible": false,

    "IsOutlineShown": false,

    "IsPageBreakPreview": false,

    "IsVisible": false,

    "IsProtected": false,

    "IsRowColumnHeadersVisible": false,

    "IsRulerVisible": false,

    "IsSelected": false,

    "TabColor": {

      "A": "0",

      "R": "0",

      "G": "0",

      "B": "0"

    },

    "TransitionEntry": false,

    "TransitionEvaluation": false,

    "Type": "Worksheet",

    "ViewType": "NormalView",

    "VisibilityType": "Hidden",

    "Zoom": 100,

    "Cells": {

      "link": {

        "Href": "/cells",

        "Rel": "self"

      }

    },

    "Charts": {

      "link": {

        "Href": "/charts",

        "Rel": "self"

      }

    },

    "AutoShapes": {

      "link": {

        "Href": "/shapes",

        "Rel": "self"

      }

    },

    "OleObjects": {

      "link": {

        "Href": "/oleobjects",

        "Rel": "self"

      }

    },

    "Comments": {

      "link": {

        "Href": "/comments",

        "Rel": "self"

      }

    },

    "Pictures": {

      "link": {

        "Href": "/pictures",

        "Rel": "self"

      }

    },

    "MergedCells": {

      "link": {

        "Href": "/mergedcells",

        "Rel": "self"

      }

    },

    "Validations": {

      "link": {

        "Href": "/validations",

        "Rel": "self"

      }

    },

    "ConditionalFormattings": {

      "link": {

        "Href": "/conditionalformattings",

        "Rel": "self"

      }

    },

    "Hyperlinks": {

      "link": {

        "Href": "/hyperlinks",

        "Rel": "self"

      }

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

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Worksheet-HideWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-worksheet-HideWorksheet-hide-worksheets.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Worksheet-PutChangeVisibilityWorksheet-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-change_worksheet_visibility-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "HideExcelWorkSheets.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Worksheet-HideWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-worksheet-HideWorksheet-hide-worksheets.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Worksheet-HideWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "cb5a1656cea2f870f0a5ef6d066525ef" >}}

{{< /tab >}}

{{< /tabs >}}
