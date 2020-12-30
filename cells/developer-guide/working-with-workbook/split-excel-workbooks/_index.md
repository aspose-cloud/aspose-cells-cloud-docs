---
title: "Split Excel Workbooks"
type: docs
url: /split-excel-workbooks/
keywords: "split worksheets, xlsx, xls, csv, google sheet, separate workbook, REST API, Python code snippet, Perl code snippet, Swift code snippet, PHP code snippet"
description: "Split all or specific worksheet of a workbook into PNG, TIFF or any other supported image format. Split XLSX worksheet using Aspose.Cells Cloud API for Ruby, Python, Perl, Java, .NET, android and many other platforms."
weight: 130
---

## **Introduction**
This example allows you to split all or specific worksheets of a workbook file and save each worksheet as a new workbook, TIFF or any supported image format using Aspose.Cells Cloud API in your applications.
## **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/{name}/split|POST|Split an Excel Workbook|[PostWorkbookSplit](https://apireference.aspose.cloud/cells/#/Workbook/PostWorkbookSplit)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/split?format=jpeg&from=1&to=1&horizontalResolution=0&verticalResolution=0" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Result": {

    "Documents": [

      {

        "Id": 1,

        "link": {

          "Href": "413e3375-c163-4d5c-8b84-8f95f63902f6.png",

          "Rel": null,

          "Title": null,

          "Type": null

        }

      }

    ]

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
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorkbookPostWorkbookSplit.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-workbook-SplitWorkbooks-split-excel-workbooks.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostWorkbookSplit-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-split_workbook-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "SplitExcelWorkbooks.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Workbook-SplitWorkbooks-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-workbook-SplitWorkbooks-split-excel-workbooks.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Workbook-SplitWorkbooks-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "ec45ec662143f4c94c2a8bc8c95953ce" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< gist "aspose-cloud" "6ddbdc7793cac6e13ad09bbfbc44a614" >}}

{{< /tab >}}

{{< /tabs >}}
