---
title: "Get AutoFilter Description"
type: docs
url: /get-autofilter-description/
weight: 10
---

## **Introduction**
This example shows how to get AutoFilter description using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/autoFilter|GET|Get auto filters description in worksheet|[GetWorksheetAutoFilter](https://apireference.aspose.cloud/cells/#/AutoFilter/GetWorksheetAutoFilter)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X GET "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/autoFilter"-H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {
  "Status": "string",
  "AutoFilter": {
    "link": {
      "Href": "string",
      "Rel": "string",
      "Title": "string",
      "Type": "string"
    },
    "FilterColumns": [
      {
        "FieldIndex": 0,
        "FilterType": "string",
        "MultipleFilters": {
          "MatchBlank": true,
          "MultipleFilterList": [
            {}
          ]
        },
        "ColorFilter": {
          "FilterByFillColor": "string",
          "Pattern": "string",
          "Color": {
            "Color": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "ColorIndex": 0,
            "IsShapeColor": true,
            "ThemeColor": {
              "ColorType": "string",
              "Tint": 0
            },
            "Type": "string"
          },
          "ForegroundColorColor": {
            "Color": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "ColorIndex": 0,
            "IsShapeColor": true,
            "ThemeColor": {
              "ColorType": "string",
              "Tint": 0
            },
            "Type": "string"
          },
          "BackgroundColor": {
            "Color": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "ColorIndex": 0,
            "IsShapeColor": true,
            "ThemeColor": {
              "ColorType": "string",
              "Tint": 0
            },
            "Type": "string"
          }
        },
        "CustomFilters": [
          {
            "FilterOperatorType": "string"
          }
        ],
        "DynamicFilter": {
          "DynamicFilterType": "string"
        },
        "IconFilter": {
          "IconId": 0,
          "IconSetType": "string"
        },
        "Top10Filter": {
          "Criteria": "string",
          "IsPercent": true,
          "IsTop": true,
          "Items": 0
        },
        "Visibledropdown": "string"
      }
    ],
    "Range": "string",
    "Sorter": {
      "CaseSensitive": true,
      "HasHeaders": true,
      "KeyList": [
        {
          "Key": 0,
          "SortOrder": "string",
          "CustomList": "string"
        }
      ],
      "SortLeftToRight": true
    }
  }
}
```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="8" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Android" tabName7="Perl" tabName8="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-Worksheet-GetWorksheetAutoFilter-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-filters-GetAutoFilterDescriptionExample-1.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-AutoFilter-GetWorksheetAutoFilter-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-AutoFilter-get_worksheet_auto_filter-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Worksheet-GetWorksheetAutoFilter-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cells" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-filters-AddDateWorksheetExample-1.java" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Worksheet-GetWorksheetAutoFilter-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "4258eab6a50d4856861377a108d0c7dd" >}}

{{< /tab >}}

{{< /tabs >}}
