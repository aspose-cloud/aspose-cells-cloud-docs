---
title: "Create an Empty Excel Workbook"
type: docs
url: /create-an-empty-excel-workbook/
weight: 20
---

## **Introduction**
This example shows how to create an empty workbook using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}|PUT|Create an Empty WorkBook|[PutWorkbookCreate](https://apireference.aspose.cloud/cells/#/Workbook/PutWorkbookCreate)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/newworkbook.xlsx?appSID=XXXX&signature=XXXX" \

     -X PUT \

     -H "Content-Type: application/json" \

     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Workbook": {

    "FileName": "newworkbook\_01.xlsx",

    "Links": [

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "self"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "text/csv",

        "Title": "Download As CSV"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "text/html",

        "Title": "Download As HTML"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "application/vnd.oasis.opendocument.spreadsheet",

        "Title": "Download As ODS"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "application/pdf",

        "Title": "Download As PDF"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "text/plain",

        "Title": "Download As Table Delimited Text Format"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "image/tiff",

        "Title": "Download As TIFF"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "application/vnd.ms-excel",

        "Title": "Download As Microsoft Excel 2003"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet",

        "Title": "Download As Microsoft Excel 2007"

      },

      {

        "Href": "http://api.aspose.cloud/v3.0/cells/newworkbook\_01.xlsx",

        "Rel": "alternate",

        "Type": "application/vnd.ms-xpsdocument",

        "Title": "Download As XPS"

      }

    ],

    "Worksheets": {

      "link": {

        "Href": "/worksheets",

        "Rel": "self"

      }

    },

    "DefaultStyle": {

      "link": {

        "Href": "/defaultstyle",

        "Rel": "self"

      }

    },

    "DocumentProperties": {

      "link": {

        "Href": "/documentproperties",

        "Rel": "self"

      }

    },

    "Names": {

      "link": {

        "Href": "/names",

        "Rel": "self"

      }

    },

    "Settings": {

      "link": {

        "Href": "/settings",

        "Rel": "self"

      }

    },

    "IsWriteProtected": "False",

    "IsProtected": "False",

    "IsEncryption": "false"

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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Java" tabName3="Perl" tabName4="Go" tabName5="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorkbookPutWorkbookCreate.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Workbook-CreateEmptyWorkbook-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "ad2ef2b72254d01920fc05d3ae506375" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "9e868bc0e2c275d9552372e65ca554b3" >}}

{{< /tab >}}

{{< /tabs >}}
