---
title: "Filter a list using a Color Filter"
type: docs
url: /filter-a-list-using-a-color-filter/
weight: 100
---

## **Introduction**
This example shows how to filter a list using a color filter with Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/autoFilter/colorFilter|PUT|Adds a color filter in worksheet|[PutWorksheetColorFilter](https://apireference.aspose.cloud/cells/#/AutoFilter/PutWorksheetColorFilter)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/autoFilter/colorFilter?range=A1:B1&fieldIndex=0&matchBlanks=true&appSID=xxxx&signature=xxxx" \

-X PUT \

-d '{

  "Pattern": "Solid",

  "ForegroundColor": {

    "Color": {

      "A": "255",

      "R": "0",

      "G": "255",

      "B": "255"

    },

    "ThemeColor": {

      "ColorType": "Text2",

      "Tint": "1"

    },

    "Type": "Automatic"

  },

  "BackgroundColor": {

    "Color": {

      "A": "255",

      "R": "255",

      "G": "0",

      "B": "0"

    },

    "ThemeColor": {

      "ColorType": "Text2",

      "Tint": "1"

    },

    "Type": "Automatic"

  }

}' \

-H "Content-Type: application/json" \

-H "Accept: application/json"

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
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Node.js" tabName5="Perl" tabName6="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-Worksheet-FilterListUsingColorFilter-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-AutoFilter-PutWorksheetColorFilter-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-AutoFilter-put\_worksheet\_color\_filter-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Worksheet-FilterListUsingColorFilter-1.js" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Worksheet-FilterListUsingColorFilter-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "96fa12d386e68fa3315f16730e951b87" >}}

{{< /tab >}}

{{< /tabs >}}
