---
title: "Get Conditional Formatting"
type: docs
url: /get-conditional-formatting/
weight: 20
---

## **Introduction**
This example shows how to get conditional formatting of a worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/conditionalFormattings/{index}|GET|Gets conditional formatting description in worksheet|[GetWorksheetConditionalFormatting](https://apireference.aspose.cloud/cells/#/ConditionalFormattings/GetWorksheetConditionalFormatting)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet1/conditionalFormattings/0" -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Status": "string",
  "ConditionalFormatting": {
    "link": {
      "Href": "string",
      "Rel": "string",
      "Title": "string",
      "Type": "string"
    },
    "sqref": "string",
    "FormatConditions": [
      {
        "link": {
          "Href": "string",
          "Rel": "string",
          "Title": "string",
          "Type": "string"
        },
        "Priority": 0,
        "Type": "string",
        "StopIfTrue": true,
        "AboveAverage": {
          "IsAboveAverage": true,
          "IsEqualAverage": true,
          "StdDev": 0
        },
        "ColorScale": {
          "MaxCfvo": {
            "IsGTE": true,
            "Type": "string"
          },
          "MaxColor": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          },
          "MidCfvo": {
            "IsGTE": true,
            "Type": "string"
          },
          "MidColor": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          },
          "MinCfvo": {
            "IsGTE": true,
            "Type": "string"
          },
          "MinColor": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          }
        },
        "DataBar": {
          "AxisColor": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          },
          "AxisPosition": "string",
          "BarBorder": {
            "Color": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "Type": "string"
          },
          "BarFillType": "string",
          "Color": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          },
          "Direction": "string",
          "MaxCfvo": {
            "IsGTE": true,
            "Type": "string"
          },
          "MaxLength": 0,
          "MinCfvo": {
            "IsGTE": true,
            "Type": "string"
          },
          "MinLength": 0,
          "NegativeBarFormat": {
            "BorderColor": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "BorderColorType": "string",
            "Color": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "ColorType": "string"
          },
          "ShowValue": true
        },
        "Formula1": "string",
        "Formula2": "string",
        "IconSet": {
          "CfIcons": [
            {
              "ImageData": "string",
              "Index": 0,
              "Type": "string"
            }
          ],
          "Cfvos": [
            {
              "IsGTE": true,
              "Type": "string"
            }
          ],
          "IsCustom": true,
          "Reverse": true,
          "ShowValue": true,
          "IconSetType": "string"
        },
        "Operator": "string",
        "Style": {
          "link": {
            "Href": "string",
            "Rel": "string",
            "Title": "string",
            "Type": "string"
          },
          "Font": {
            "Color": {
              "A": 0,
              "R": 0,
              "G": 0,
              "B": 0
            },
            "DoubleSize": 0,
            "IsBold": true,
            "IsItalic": true,
            "IsStrikeout": true,
            "IsSubscript": true,
            "IsSuperscript": true,
            "Name": "string",
            "Size": 0,
            "Underline": "string"
          },
          "Name": "string",
          "CultureCustom": "string",
          "Custom": "string",
          "BackgroundColor": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          },
          "ForegroundColor": {
            "A": 0,
            "R": 0,
            "G": 0,
            "B": 0
          },
          "IsFormulaHidden": true,
          "IsDateTime": true,
          "IsTextWrapped": true,
          "IsGradient": true,
          "IsLocked": true,
          "IsPercent": true,
          "ShrinkToFit": true,
          "IndentLevel": 0,
          "Number": 0,
          "RotationAngle": 0,
          "Pattern": "string",
          "TextDirection": "string",
          "VerticalAlignment": "string",
          "HorizontalAlignment": "string",
          "BorderCollection": [
            {
              "LineStyle": "string",
              "Color": {
                "A": 0,
                "R": 0,
                "G": 0,
                "B": 0
              },
              "BorderType": "string"
            }
          ],
          "BackgroundThemeColor": {
            "ColorType": "string",
            "Tint": 0
          },
          "ForegroundThemeColor": {
            "ColorType": "string",
            "Tint": 0
          }
        },
        "Text": "string",
        "TimePeriod": "string",
        "Top10": {
          "IsBottom": true,
          "IsPercent": true,
          "Rank": 0
        }
      }
    ]
  }
}
```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Python" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}



{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNet-CSharp-ConditionalFormatting-GetConditionalFormatting-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-cells-get-conditional-formatting-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}



{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-ConditionalFormatting-get_worksheet_conditional_formatting-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}



{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-ConditionalFormatting-GetConditionalFormatting-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}



{{< /tab >}}

{{< tab tabNum="7" >}}



{{< /tab >}}

{{< tab tabNum="8" >}}



{{< /tab >}}

{{< tab tabNum="9" >}}



{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-ConditionalFormatting-GetConditionalFormatting-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}



{{< gist "aspose-cloud" "d1809f85075aaa2f4d954930e916d115" >}}

{{< /tab >}}

{{< /tabs >}}
