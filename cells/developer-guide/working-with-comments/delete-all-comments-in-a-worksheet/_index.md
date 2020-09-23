---
title: "Delete All Comments in a Worksheet"
type: docs
url: /delete-all-comments-in-a-worksheet/
weight: 40
---

## **Introduction**
This example shows how to delete comments from a Excel Worksheet using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments|POST|Get worksheet comments|[DeleteWorkSheetComments](https://apireference.aspose.cloud/cells/#/Worksheets/DeleteWorkSheetComments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments" -H "accept: application/json"
```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Comments": {

    "CommentList": [],

    "link": {

      "Href": "/test.xlsx/worksheets/Sheet1/comments",

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

{{< gist "aspose-cloud" "51c3a018dbaff3df7cd2244f21845bdc" >}}

{{< /tab >}}

{{< /tabs >}}
