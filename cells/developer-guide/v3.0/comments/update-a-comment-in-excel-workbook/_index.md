---
title: "Update a comment in Excel Workbook"
type: docs
url: /update-a-comment-in-excel-workbook/
weight: 30
---

## **Introduction**
This example shows how to update a comment in a worksheet, using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments/{cellName}|POST|Get worksheet comments|[PostWorkSheetComment](https://apireference.aspose.cloud/cells/#/Worksheets/PostWorkSheetComment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments/a1" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"CellName\": \"a1\", \"Author\": \"test\", \"HtmlNote\": \"string\", \"Note\": \"this is a comment\", \"AutoSize\": true, \"IsVisible\": true, \"Width\": 10, \"Height\": 10}"

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
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="1" tabID="4" tabName1="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "bf512f63ac7d0c31f9a0f1008cd3e031" >}}

{{< /tab >}}

{{< /tabs >}}




