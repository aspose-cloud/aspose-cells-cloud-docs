---
title: "Get Comment from a Worksheet"
type: docs
url: /get-comment-from-a-worksheet/
weight: 10
---

## **Introduction**
This example shows how to read comments from a worksheet, using Aspose.Cells Cloud in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/comments|DELETE|Delete Worksheet comments|[GetWorkSheetComments](https://apireference.aspose.cloud/cells/#/Worksheets/GetWorkSheetComments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/Sheet1/comments" -H "accept: application/json"

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

{{< gist "aspose-cloud" "0f1e96858d650d16d9c09ca61723c335" >}}

{{< /tab >}}

{{< /tabs >}}
