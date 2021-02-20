---
title: "Set Background or Watermark for Excel Worksheet"
type: docs
url: /set-background-or-watermark-for-excel-worksheet/
weight: 180
---

## **Introduction**
This example shows how to set a background image or watermark image for a worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/background|PUT|Sets background image in worksheet|[PutWorkSheetBackground](https://apireference.aspose.cloud/cells/#/Worksheets/PutWorkSheetBackground)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "http://api.aspose.com/v3.0/cells/myWorkbook.xlsx/worksheets/Sheet1/background" -T Creative.jpg -H "Content-Type: multipart/form-data" -H "Accept: application/json"

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
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorksheetsPutWorkSheetBackground.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}



{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5c1a68c4cea73845b221ff0d3b9ec9df" "Examples-PHP-Worksheet-PutWorkSheetBackground-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "3c5c9f9fff9898bb8251aa7ee9191641" "Examples-Ruby-Worksheet-set_worksheet_background_image-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}



{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "SetBackgroundOrWatermark.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Worksheet-SetWatermarkBackground-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-worksheet-SetWatermarkBackground-set-watermark-background.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Worksheet-SetWatermarkBackground-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "55687418c026c00dc13524ab7da2a722" >}}

{{< /tab >}}

{{< /tabs >}}
