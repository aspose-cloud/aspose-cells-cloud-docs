---
title: "Create Excel Workbook from a SmartMarker Template"
type: docs
url: /create-excel-workbook-from-a-smartmarker-template/
weight: 40
---

## **Introduction**
This example shows how to create a workbook from a SmartMarker template file using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/{name}/smartmarker|POST|Create a new Excel Workbook from a SmartMarker template file|[PostWorkbookGetSmartMarkerResult](https://apireference.aspose.cloud/cells/#/Workbook/PostWorkbookGetSmartMarkerResult)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v3.0/cells/newworkbook\_14.xlsx?templateFile=Sample\_SmartMarker.xlsx&dataFile=Sample\_SmartMarker\_Data.xml&appSID=XXXX&signature=XXXX" \
     -X PUT \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Workbook":{

    "FileName":"newworkbook\_14.xlsx",

    "Links":[

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"self"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"text/csv",

        "Title":"Download As CSV"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"text/html",

        "Title":"Download As HTML"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"application/vnd.oasis.opendocument.spreadsheet",

        "Title":"Download As ODS"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"application/pdf",

        "Title":"Download As PDF"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"text/plain",

        "Title":"Download As Table Delimited Text Format"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"image/tiff",

        "Title":"Download As TIFF"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"application/vnd.ms-excel",

        "Title":"Download As Microsoft Excel 2003"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet",

        "Title":"Download As Microsoft Excel 2007"

      },

      {

        "Href":"http://api.aspose.cloud/v3.0/cells/newworkbook\_14.xlsx",

        "Rel":"alternate",

        "Type":"application/vnd.ms-xpsdocument",

        "Title":"Download As XPS"

      }

    ],

    "Worksheets":{

      "link":{

        "Href":"/worksheets",

        "Rel":"self"

      }

    },

    "DefaultStyle":{

      "link":{

        "Href":"/defaultstyle",

        "Rel":"self"

      }

    },

    "DocumentProperties":{

      "link":{

        "Href":"/documentproperties",

        "Rel":"self"

      }

    },

    "Names":{

      "link":{

        "Href":"/names",

        "Rel":"self"

      }

    },

    "Settings":{

      "link":{

        "Href":"/settings",

        "Rel":"self"

      }

    },

    "IsWriteProtected":"False",

    "IsProtected":"False",

    "IsEncryption":"false"

  },

  "Code":"200",

  "Status":"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorkbookPostWorkbookGetSmartMarkerResult.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-workbook-CreateWorkbookFromSmartMarkerTemplate-create-from-smart-marker.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PutWorkbookCreate-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-create\_new\_workbook-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "CreateExcelWorkbookFromSmartMarkerTemplate.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Workbook-CreateWorkbookFromSmartMakerTemplate-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-workbook-CreateWorkbookFromSmartMarkerTemplate-create-from-smart-marker.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Workbook-CreateWorkbookFromSmartMakerTemplate-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "42b369351a3909d9f38916d9f6e10d9a" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< gist "aspose-cloud" "f83596a0e742321c1a0296332804d047" >}}

{{< /tab >}}

{{< /tabs >}}
