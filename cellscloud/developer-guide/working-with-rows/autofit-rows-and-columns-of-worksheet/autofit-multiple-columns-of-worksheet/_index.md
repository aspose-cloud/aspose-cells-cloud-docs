---
title: "AutoFit Multiple Columns of Worksheet"
type: docs
url: /autofit-multiple-columns-of-worksheet/
weight: 20
---

## **Introduction**
This example shows how to autofit multiple columns of the worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/autofitcolumns|POST|Autofit columns in worksheet|[PostAutofitWorksheetColumns](https://apireference.aspose.cloud/cells/#/Worksheets/PostAutofitWorksheetColumns)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/sampleAutoFit.xlsx/worksheets/Sheet1/autofitcolumns?lastColumn=5&firstColumn=0&appSID=xxxx&signature=xxxx" \

     -X POST \

     -d '{"AutoFitMergedCells" : true, "IgnoreHidden" : true, "OnlyAuto" : true}' \

     -H "Content-Type: application/json" \

     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks-html/)
## **SDK Examples**
{{< tabs tabTotal="2" tabID="4" tabName1="C#" tabName2="Go" >}}

{{< tab tabNum="1" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< /tabs >}}
