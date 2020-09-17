---
title: "Update Excel Worksheet Properties"
type: docs
url: /update-excel-worksheet-properties/
weight: 170
---

## **Introduction**
This example shows how to update properties of a worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}|POST|Update worksheet properties|[PostUpdateWorksheetProperty](https://apireference.aspose.cloud/cells/#/Worksheets/PostUpdateWorksheetProperty)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1?appSID=xxxx&signature=xxxx" \
     -X POST \
     -d '{"DisplayRightToLeft":true, "DisplayZeros":true, "FirstVisibleColumn":1, "FirstVisibleRow":1, "Name":"sheet1", "Index":0, "IsGridlinesVisible":true, "IsOutlineShown":true, "IsPageBreakPreview":true, "IsVisible":true, "IsRowColumnHeadersVisible":true, "IsRulerVisible":true, "IsSelected":true, "TransitionEntry":true, "TransitionEvaluation":true, "Type":"Worksheet", "ViewType":"PageBreakPreview", "Zoom":80}' \
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

        "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1",

        "Rel": "self"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/tiff",

        "Title": "Download As TIFF"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/jpeg",

        "Title": "Download As Jpeg"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/png",

        "Title": "Download As Png"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/bmp",

        "Title": "Download As Bmp"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1",

        "Rel": "alternate",

        "Type": "image/gif",

        "Title": "Download As Gif"

      }

    ],

    "DisplayRightToLeft": false,

    "DisplayZeros": false,

    "FirstVisibleColumn": 1,

    "FirstVisibleRow": 1,

    "Name": "sheet1",

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

    "ViewType": "PageBreakPreview",

    "VisibilityType": "Visible",

    "Zoom": 80,

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
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Android" tabName7="Objective C" tabName8="Perl" tabName9="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorksheetsPostUpdateWorksheetProperty.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-worksheet-UpdateWorksheetProperties-update-worksheet-properties.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Worksheet-PostUpdateWorksheetProperty-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-update_worksheet_property-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Worksheet-UpdateWorksheetProperties-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-worksheet-UpdateWorksheetProperties-update-worksheet-properties.java" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Worksheet-UpdateWorksheetProperties-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "ce38cb4feb118132fada7801c7f5cd43" >}}

{{< /tab >}}

{{< /tabs >}}
