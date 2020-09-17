---
title: "Add a New Excel Worksheet"
type: docs
url: /add-a-new-excel-worksheet/
weight: 20
---

## **Introduction**
This example shows how to add a new worksheet in a workbook using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}|PUT|Adds new worksheet in workbook|[PutAddNewWorksheet](https://apireference.aspose.cloud/cells/#/Worksheets/PutAddNewWorksheet)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v3.0/cells/myWorkbook.xlsx/worksheets/Tasks?appSID=xxxx&signature=xxxx" \
     -X PUT \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

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

      },

      {

        "link": {

          "Href": "/Tasks",

          "Rel": "self"

        }

      }

    ],

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/worksheets",

      "Rel": "self"

    }

  },

  "Code": "201",

  "Status": "Created"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorksheetsPutAddNewWorksheet.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-worksheet-AddNewSheet-add-new-excel-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Worksheet-PutAddNewWorksheet-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-add\_new\_worksheet-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "AddNewExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Worksheet-AddNewSheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-worksheet-AddNewSheet-add-new-excel-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Worksheet-AddNewSheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

|

{{< gist "aspose-cloud" "f03965c178d22319d9de9838eda25260" >}}

{{< /tab >}}

{{< /tabs >}}

![todo:image\_alt\_text](/images/icons/grey\_arrow\_down.png)

Perl

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Worksheet-AddNewSheet-1.pl" >}}
