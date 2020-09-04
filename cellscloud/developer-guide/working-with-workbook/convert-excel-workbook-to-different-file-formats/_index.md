---
title: "Convert Excel Workbook to Different File Formats"
type: docs
url: /convert-excel-workbook-to-different-file-formats/
keywords: "Perl, Python, Java, .NET, dotnet, Cells into PDF, Cloud API, REST api"
description: "REST API to convert XLS XLSX into PDF and many other formats like HTML, ODS, XPS, CSV etc. SDKs are available for .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more languages."
weight: 10
---

## **Introduction**
This example shows how to convert a workbook to a different file format and save the resultant document to cloud storage using Aspose.Cells Cloud API.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/saveAs|POST|Export workbook to Format|[PostDocumentSaveAs](https://apireference.aspose.cloud/cells/#/SaveAs/PostDocumentSaveAs)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/test.xlsx/SaveAs?newfilename=test.pdf&isAutoFitRows=true&isAutoFitColumns=true" -H "accept: multipart/form-data" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1Njk2MTc1MjMsImV4cCI6MTU2OTcwMzkyMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.rumxrTCH5z-\_7N-qhiZTdzt4dn1G0nJ0TRuoSqKdUS\_roU7SGJn\_JCA45ZsYibCLDJvsHfMQN7KnAijgKlPSqNQ6cuXnqKPaQdgfc\_uEqLKNu91HIYJVX69lvI1FzoFpfpPpDc2E07MMBt\_5373xkbQ53N6bMhJk4qES53Of5mENcCm1es9gXLytlUVNmrE-uQdMHLfVsERmO6YNOWxLS5bCx3OCVcBNkVCZMsGyzMOGH9JmJ0nUoaASlqTuct8zqzhw2TSnwxBuViOVI8v6a\_P6o\_JfSnkaZ6\_coreQ1ET3CoXtn1Itpt8FNCXlcSEDu7ynF8FmXxS0Vs1c1HtiwA"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "SaveResult": {

    "SourceDocument": {

      "Href": "test.xlsx",

      "Rel": null,

      "Title": null,

      "Type": null

    },

    "DestDocument": {

      "Href": "test.pdf",

      "Rel": null,

      "Title": null,

      "Type": null

    },

    "AdditionalItems": []

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
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Python" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Workbook-ConvertToAnotherFormat-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-workbook-ConvertWorkbookToAnotherFormat-convert-workbook-to-different-format.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostDocumentSaveAs-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-post\_document\_save\_as-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Workbook-ConvertToAnotherFormat-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "ConvertExcelToVariousFormats.py" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-workbook-ConvertWorkbookToAnotherFormat-convert-workbook-to-different-format.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Workbook-ConvertToAnotherFormat-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< /tab >}}

{{< /tabs >}}
