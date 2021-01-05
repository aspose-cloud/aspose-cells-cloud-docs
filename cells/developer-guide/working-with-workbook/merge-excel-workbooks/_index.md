---
title: "Merge Excel Workbooks"
type: docs
url: /merge-excel-workbooks/
weight: 50
---

## **Introduction**
This example shows how to merge multiple workbooks into a single workbook using Aspose.Cells Cloud API in your applications.  Aspose.Cells Cloud provides the following API. The API accepts a source and a destination Excel file that is uploaded to the Cloud Storage
## **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/{name}/merge|POST|Merge Excel Workbooks|[PostWorkbooksMerge](https://apireference.aspose.cloud/cells/#/Workbook/PostWorkbooksMerge)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/merge?mergeWith=test2.xlsx" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Workbook": {

    "FileName": "test.xlsx",

    "Links": [

      {

        "Href": "/test.xlsx",

        "Rel": "self",

        "Title": null,

        "Type": null

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As CSV",

        "Type": "text/csv"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As HTML",

        "Type": "text/html"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As ODS",

        "Type": "application/vnd.oasis.opendocument.spreadsheet"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As PDF",

        "Type": "application/pdf"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As Table Delimited Text Format",

        "Type": "text/plain"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As TIFF",

        "Type": "image/tiff"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As Microsoft Excel 2003",

        "Type": "application/vnd.ms-excel"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As Microsoft Excel 2007",

        "Type": "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"

      },

      {

        "Href": "/test.xlsx",

        "Rel": "alternate",

        "Title": "Download As XPS",

        "Type": "application/vnd.ms-xpsdocument"

      }

    ],

    "Worksheets": {

      "link": {

        "Href": "/worksheets",

        "Rel": "self",

        "Title": null,

        "Type": null

      }

    },

    "DefaultStyle": {

      "link": {

        "Href": "/defaultstyle",

        "Rel": "self",

        "Title": null,

        "Type": null

      }

    },

    "DocumentProperties": {

      "link": {

        "Href": "/documentproperties",

        "Rel": "self",

        "Title": null,

        "Type": null

      }

    },

    "Names": {

      "link": {

        "Href": "/names",

        "Rel": "self",

        "Title": null,

        "Type": null

      }

    },

    "Settings": {

      "link": {

        "Href": "/settings",

        "Rel": "self",

        "Title": null,

        "Type": null

      }

    },

    "IsWriteProtected": "False",

    "IsProtected": "False",

    "IsEncryption": "false",

    "Password": null

  },

  "Code": 200,

  "Status": "OK"

}


Response headers


```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorkbookPostWorkbooksMerge.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-workbook-MergeWorkbooks-merge-excel-workbooks.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5c1a68c4cea73845b221ff0d3b9ec9df" "Examples-PHP-Workbook-PostWorkbooksMerge-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-merge_workbooks-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "MergeExcelWorkbooks.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Workbook-MergeWorkbooks-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-workbook-MergeWorkbooks-merge-excel-workbooks.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Workbook-MergeWorkbooks-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "c1a1b01c65fb7af8a56a09412fb3a6cf" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< gist "aspose-cloud" "d010d44b4ecd78fbc05fef9ec61146f9" >}}

{{< /tab >}}

{{< /tabs >}}
