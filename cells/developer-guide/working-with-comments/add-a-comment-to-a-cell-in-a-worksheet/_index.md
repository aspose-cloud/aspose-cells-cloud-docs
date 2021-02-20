---
title: "Add a comment to a Cell in a Worksheet"
type: docs
url: /add-a-comment-to-a-cell-in-a-worksheet/
weight: 20
---

## **Introduction**
This example shows how to add a comments from a worksheet, using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments/{cellName}|POST|Add a worksheet comments|[PutWorkSheetComment](https://apireference.aspose.cloud/cells/#/Worksheets/PutWorkSheetComment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments/a1" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"CellName\": \"a1\", \"Author\": \"test\", \"HtmlNote\": \"string\", \"Note\": \"this is a comment\", \"AutoSize\": true, \"IsVisible\": true, \"Width\": 10, \"Height\": 10}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Comment": {

    "CellName": "A1",

    "Author": "test",

    "HtmlNote": "<Font Style=\"FONT-WEIGHT: bold;FONT-FAMILY: Tahoma;FONT-SIZE: 9pt;COLOR: #000000;TEXT-ALIGN: left;\">this is a comment</Font>",

    "Note": "this is a comment",

    "AutoSize": true,

    "IsVisible": true,

    "Width": 10,

    "Height": 10,

    "TextHorizontalAlignment": "Left",

    "TextOrientationType": "NoRotation",

    "TextVerticalAlignment": "Top",

    "link": {

      "Href": "/test.xlsx/worksheets/Sheet1/comments/a1",

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
{{< tabs tabTotal="1" tabID="4" tabName1="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "6e4a5c5c04cab925b7125b533afeba01" >}}

{{< /tab >}}

{{< /tabs >}}
