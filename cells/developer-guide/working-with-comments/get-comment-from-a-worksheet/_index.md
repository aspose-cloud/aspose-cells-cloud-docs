---
title: "Get Comment from a Worksheet"
type: docs
url: /get-comment-from-a-worksheet/
weight: 10
---

## **Introduction**
This example shows how to read comments from a Excel Worksheet using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments|DELETE|Delete Worksheet comments|[GetWorkSheetComments](https://apireference.aspose.cloud/cells/#/Worksheets/GetWorkSheetComments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NzIxMjg1NjksImV4cCI6MTU3MjIxNDk2OSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.kvV6RFY-MK-g83pQJh9-QdeU_fo2FMruLrBIoCPbUIpZjbCZaM4WjI0RsrzoE51l079haVSndHreIiN-vLwcvqZHTd_yTr29sSAIcEFuXH4vaUjh4Xn6J0_iPLkJLwOmnu0tZ0l5x_SduzH-LAF_x2K5L2cMYzn56WygWbmAaqjTs1cUFakLjMl9tKmsa1G03P3AiDjW9gXEt3jZ6sj9e_tpHmr5M22ZJAX_fhux2uem4XB3Tvi4DtEHZbqWqCmdKeW_WC0adrM6ggeBNDGx-jXiJCklBT81IDtt9WK7Tz7js1A-vyqj8L3JL9S6eO5vafjpluIHgsicJuuuGwNyVA"

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

{{< gist "aspose-cloud" "0f1e96858d650d16d9c09ca61723c335" >}}

{{< /tab >}}

{{< /tabs >}}
