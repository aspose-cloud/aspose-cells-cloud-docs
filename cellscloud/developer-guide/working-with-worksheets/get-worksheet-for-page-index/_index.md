---
title: "Get Worksheet for Page Index"
type: docs
url: /get-worksheet-for-page-index/
weight: 240
---

## **Introduction**
This example shows how to get a specific worksheet page to image using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}|GET|Gets worksheet in some format|[GetWorkSheetWithFormat](https://apireference.aspose.cloud/cells/#/Worksheets/GetWorkSheetWithFormat)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1?format=png&verticalResolution=100&horizontalResolution=90&pageIndex=1&folder=DotnetFiles" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

Converted Image 

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="7" tabID="4" tabName1="C#" tabName2="Java" tabName3="Python" tabName4="Android" tabName5="Ruby" tabName6="PHP" tabName7="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "c26975dacdc050fccd6d003b487b39d9" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "a555abf44e31590c6ae3260c1bcd3066" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "3c7008ae0d54a40cd0c92a1273bfd7d5" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "bd5c03f09104b9d59941d6583117dce2" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "64a33901d4f45c9edf31ab83e816981e" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "daa94750c751cb595de0b8a357c051ed" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "a4bb7786b0d6bc98d8b51da49a687cf5" >}}

{{< /tab >}}

{{< /tabs >}}
