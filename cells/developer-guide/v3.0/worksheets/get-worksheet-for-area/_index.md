---
title: "Get Worksheet for Area"
type: docs
url: /get-worksheet-for-area/
weight: 230
---

## **Introduction**
This example shows how to get a worksheet area to image using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}|GET|Gets worksheet in some format|[GetWorkSheetWithFormat](https://apireference.aspose.cloud/cells/#/Worksheets/GetWorkSheetWithFormat)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1?format=png&verticalResolution=100&horizontalResolution=90&area=B3%3AK8&folder=DotnetFiles" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

Converted Image 

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="7" tabID="4" tabName1="C#" tabName2="Java" tabName3="Python" tabName4="Android" tabName5="Ruby" tabName6="PHP" tabName7="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "9550c8e96c1d39b03fdf58053a5e79e2" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "9031223dee8a678505878e887533df4a" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "16dee84a0846f649727b066f20732da0" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "b36476d85ae21a2368ee4eed6fe478e9" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "cbb9cd7b55aa4264f994658831fb8e77" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "b261f08e109d3d64e4ffc9ffe128e3f3" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "638d99f44813b9d6139967bc6fb43ecd" >}}

{{< /tab >}}

{{< /tabs >}}
