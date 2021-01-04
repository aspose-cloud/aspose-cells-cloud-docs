---
title: "Get Worksheet Count"
type: docs
url: /get-worksheet-count/
weight: 10
---

## **Introduction**
This example shows how to get worksheet count using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets|GET|Get worksheets description|[GetWorkSheets](https://apireference.aspose.cloud/cells/#/Worksheets/GetWorkSheets)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "http://api.aspose.com/v3.0/cells/myWorkbook.xlsx/worksheets" -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Worksheets": {

    "WorksheetList": [

      {

        "link": {

          "Href": "/Sheet1",

          "Rel": "self"

        }

      },

      {

        "link": {

          "Href": "/Sheet2",

          "Rel": "self"

        }

      }

    ],

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets",

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
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorksheetsGetWorkSheet.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-worksheet-GetWorksheetCount-get-worksheet-count.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Worksheet-GetWorkSheets-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-read_worksheets_info-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "GetWorksheetCount.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Worksheet-GetWorksheetCount-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-worksheet-GetWorksheetCount-get-worksheet-count.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Worksheet-GetWorksheetCount-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "9c2fd1ec4e332046f7371385401be3e9" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< gist "aspose-cloud" "e2baa7ef972b3a3af2300c61caa0d6c2" >}}

{{< /tab >}}

{{< /tabs >}}
