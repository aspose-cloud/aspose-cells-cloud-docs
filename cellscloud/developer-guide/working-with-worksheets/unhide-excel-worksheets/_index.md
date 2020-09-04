---
title: "Unhide Excel Worksheets"
type: docs
url: /unhide-excel-worksheets/
weight: 60
---

## **Introduction**
This example shows how to unhide a worksheet in a workbook using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/visible|PUT|Changes worksheet visibility|[PutChangeVisibilityWorksheet](https://apireference.aspose.cloud/cells/#/Worksheets/PutChangeVisibilityWorksheet)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v/cells/Sample\_Test\_Book.xls/worksheets/Sheet1/visible?isVisible=true&appSID=xxxx&signature=xxxx" \

     -X PUT \

     -H "Content-Type: application/json" \

     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Worksheet": {

    "Links": [

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample\_Test\_Book.xls/worksheets/Sheet1",

        "Rel": "self"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample\_Test\_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/tiff",

        "Title": "Download As TIFF"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample\_Test\_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/jpeg",

        "Title": "Download As Jpeg"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample\_Test\_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/png",

        "Title": "Download As Png"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample\_Test\_Book.xls/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/bmp",

        "Title": "Download As Bmp"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/Sample\_Test\_Book.xls/worksheets/Sheet1",

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

    "VisibilityType": "Visible",

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
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Perl" tabName8="Android" tabName9="Objective C" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Worksheet-UnhideWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-worksheet-UnhideWorksheet-unhide-worksheets.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Worksheet-PutChangeVisibilityWorksheet-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-change\_worksheet\_visibility-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "UnhideExcelWorksheets.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Worksheet-UnhideWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Worksheet-UnhideWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-worksheet-UnhideWorksheet-unhide-worksheets.java" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< /tab >}}

{{< /tabs >}}
