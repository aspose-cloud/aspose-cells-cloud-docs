---
title: "Get Validation from a Worksheet"
type: docs
url: /get-validation-from-a-worksheet/
weight: 100
---

## **Introduction**
This example shows how to get validation from a worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/validations|GET|Get validations description in worksheet|[GetWorkSheetValidations](https://apireference.aspose.cloud/cells/#/WorksheetValidations/GetWorkSheetValidations)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "http://api.aspose.com/v3.0/cells/myWorkBook.xlsx/worksheets/Sheet1/validations?range=A1:C10" -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Validation": {

    "AlertStyle": "Stop",

    "AreaList": [

      {

        "EndColumn": 0,

        "EndRow": 0,

        "StartColumn": 0,

        "StartRow": 0

      },

      {

        "EndColumn": 27,

        "EndRow": 0,

        "StartColumn": 26,

        "StartRow": 0

      }

    ],

    "IgnoreBlank": false,

    "InCellDropDown": false,

    "Operator": "None",

    "ShowError": false,

    "ShowInput": false,

    "Type": "AnyValue",

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/myWorkBook.xlsx/worksheets/Sheet1/Validations/0",

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
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-Worksheet-GetValidation-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-worksheet-GetValidation-get-validation-from-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5c1a68c4cea73845b221ff0d3b9ec9df" "Examples-PHP-Worksheet-GetWorkSheetValidation-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "3c5c9f9fff9898bb8251aa7ee9191641" "Examples-Ruby-Worksheet-get_worksheet_validation_by_index-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "GetValidationFromWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Worksheet-GetValidation-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-worksheet-GetValidation-get-validation-from-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Worksheet-GetValidation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "a8019ee08de05cb0e97ef9c75f9cdf46" >}}

{{< /tab >}}

{{< /tabs >}}
