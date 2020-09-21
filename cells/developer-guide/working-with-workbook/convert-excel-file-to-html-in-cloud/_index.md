---
title: "Convert Excel File to HTML in Cloud"
type: docs
url: /convert-excel-file-to-html-in-cloud/
weight: 150
---

## **Introduction**
This example shows how to convert excel file to HTML using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/convert|PUT|Converts workbook from request content to some format|[PutConvertWorkBook](https://apireference.aspose.cloud/cells/#/Workbook/PutConvertWorkBook)|
### **cURL Example**
{{< tabs tabTotal="1" tabID="1" tabName1="Request" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/cells/convert?format=html" -H "accept: multipart/form-data" -H "Content-Type: multipart/form-data" -H "x-aspose-client: Containerize.Swagger" -d {"File":{}}
```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="3" tabName1="C#" tabName2="Go" tabName3="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "00860c8ef58cebd673190e304b6ddbdf" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "3f950cf3a2682cfa62dbfa542257b744" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "701965adeefa90bfc9b8ddf2bf7eba20" >}}

{{< /tab >}}

{{< /tabs >}}
