---
title: "Delete All Comments in a Worksheet"
type: docs
url: /delete-all-comments-in-a-worksheet/
weight: 40
---

## **Introduction**
This example shows how to delete comments from a Excel Worksheet using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments|POST|Get worksheet comments|[DeleteWorkSheetComments](https://apireference.aspose.cloud/cells/#/Worksheets/DeleteWorkSheetComments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NzIxMjg1NjksImV4cCI6MTU3MjIxNDk2OSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.kvV6RFY-MK-g83pQJh9-QdeU\_fo2FMruLrBIoCPbUIpZjbCZaM4WjI0RsrzoE51l079haVSndHreIiN-vLwcvqZHTd\_yTr29sSAIcEFuXH4vaUjh4Xn6J0\_iPLkJLwOmnu0tZ0l5x\_SduzH-LAF\_x2K5L2cMYzn56WygWbmAaqjTs1cUFakLjMl9tKmsa1G03P3AiDjW9gXEt3jZ6sj9e\_tpHmr5M22ZJAX\_fhux2uem4XB3Tvi4DtEHZbqWqCmdKeW\_WC0adrM6ggeBNDGx-jXiJCklBT81IDtt9WK7Tz7js1A-vyqj8L3JL9S6eO5vafjpluIHgsicJuuuGwNyVA"

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
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="1" tabID="4" tabName1="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "51c3a018dbaff3df7cd2244f21845bdc" >}}

{{< /tab >}}

{{< /tabs >}}
