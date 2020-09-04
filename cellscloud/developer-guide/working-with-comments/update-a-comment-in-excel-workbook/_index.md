---
title: "Update a comment in Excel Workbook"
type: docs
url: /update-a-comment-in-excel-workbook/
weight: 30
---

## **Introduction**
This example shows how to update a comment in a Excel Worksheet using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments/{cellName}|POST|Get worksheet comments|[PostWorkSheetComment](https://apireference.aspose.cloud/cells/#/Worksheets/PostWorkSheetComment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments/a1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NzIxMjkzMTYsImV4cCI6MTU3MjIxNTcxNiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.EtpFm61rEM1D9A0JPZo-shO\_LjNr44DwSjur-CWnuwQU5eiNscS7Te\_\_D4JjxMGkCuVgOcF9tZKsmuI76d2P18JV5TgbO86Fp2Ky6S93s7z9KP0ezweeMOppiGkQACKNJhbA-1dOV452vWErYDBvp\_FL7w6XsbxKJWUYebB\_JOm89xsNK0WESPFFXD0O6APvwruNYs2KOX5ieODfDd3zDC4BQePJATSD8nL7Ou48O\_7rY2-DYZ5zgBBWIyTl9fANeh8wqa3RwWMUw1\_dl7dNRoFHpMy42UaN\_5fsCJD\_FCAao\_dsBb0Ly1wK4wtdC-e0LNYq6hZprYVu7r7oV2yM8g" -H "Content-Type: application/json" -d "{ \"CellName\": \"a1\", \"Author\": \"test\", \"HtmlNote\": \"string\", \"Note\": \"this is a comment\", \"AutoSize\": true, \"IsVisible\": true, \"Width\": 10, \"Height\": 10}"

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
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="1" tabID="4" tabName1="Go" >}}

{{< tab tabNum="1" >}}

{{< /tab >}}

{{< /tabs >}}




