---
title: "Add Hyperlinks to Excel Worksheet"
type: docs
url: /add-hyperlinks-to-excel-worksheet/
weight: 20
---

## **Introduction**
This example shows how to add a hyperlink to a Microsoft Excel Workbook using Aspose.Cells Cloud API.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/hyperlinks|PUT|Add a hyperlink to a Excel Workbook|[PutWorkSheetHyperlink](https://apireference.aspose.cloud/cells/#/Hypelinks/PutWorkSheetHyperlink)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/hyperlinks?firstRow=1&firstColumn=6&totalRows=1&totalColumns=1&address=https%3A%2F%2Fwww.msnbc.com%2F" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Hyperlink": {

    "Address": "https://www.msnbc.com/",

    "Area": {

      "EndColumn": 6,

      "EndRow": 1,

      "StartColumn": 6,

      "StartRow": 1

    },

    "ScreenTip": null,

    "TextToDisplay": "https://www.msnbc.com/",

    "link": {

      "Href": "/test.xlsx/worksheets/Sheet1/hyperlinks/4",

      "Rel": "self",

      "Title": null,

      "Type": null

    }

  },

  "Code": 200,

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

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Hyperlinks-AddHyperlinkWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-hyperlinks-AddHyperlinkWorksheet-add-hyperlinks-to-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Hyperlinks-PutWorkSheetHyperlink-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Hyperlinks-add_worksheet_hyperlink-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "AddHyperlinksFromExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-hyperlinks-AddHyperlinkWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-hyperlinks-AddHyperlinkWorksheet-add-hyperlinks-to-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-hyperlinks-AddHyperlinkWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "a9ac30409d4fb095eed37974c001fb67" >}}

{{< /tab >}}

{{< /tabs >}}
