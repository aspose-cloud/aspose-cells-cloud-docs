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

curl -v "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet1/conditionalFormattings/0?appSID=xxxx&signature=xxxx" \
-X GET \
-H "Content-Type: application/json" \
-H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  : ConditionalFormatting=>{

    : sqref=>"C3:D5 E7:F9 ",

    : FormatConditions=>[

      {

        : Priority=>6,

        : Type=>"IconSet",

        : StopIfTrue=>false,

        : IconSet=>{

          : CfIcons=>[

            {

              : ImageData=>"iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAFUSURBVDhPtZPPKwRxGMbnL/EHuLvIwUGKcRJKrfJjZAf5mdLWRkhKNtSkKD+WrFonh8VZuW9jc3bgsEc7v5we87xGYzPZ78V7meY738/b+z7PM9q/lF28RGnexElHK/aam+TJd55HV5Lr5fEBN+YI7lP9qGQzqFoWvLM8qrkc7IVZ3PXq8p33IiQuHhb6dDyvr+KjeI2gcIXg/ALB8Sn8wyP41gH83X1UJtNy71cTdm4Ee9s78Da38GSMyiQR+rUzx1aB3bUNuNkV3Ha2x5pQIO6sCrvLGZQHB0RYaUCVKZgq7Cwu4c0wxB1pQKuotirszMzhPT0lFksDmSC0ShV2zGm8pobiCSQkoc+qcG18AuWe7lgDqsmQqMK14TGU2lrqk0lfGRIV2Na76nPA+k4iQ9IITkwii4fszJDQZ1pFtSmY7ByOze+J8M/ibhSIKv/9N2raJ0ssJUI0Ezm0AAAAAElFTkSuQmCC",

              : Index=>0,

              : Type=>"TrafficLights31"

            },

            {

              : ImageData=>"iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAFRSURBVDhPtVM9SwNRELzKv+AvMJh/ENCUgpCABKtgKdikTCPYCNqlsBAUggqmEKxEizQRLQQDtgZJ1BDFmPMDP+6wOSE7uVkPz+BhXuM2j9v3ZtidmbP+pd6qm7gvZdFcHkE9P6Qnv9kPnkTXR+MQ7Y0M7FIK7sk8Pq/XIY878BoFOMdzsLfG9J7vAkhYbN6sJOBWF4HXMvCyBzzvQp62IQ9FSGcV0i7APcrqu18kZB4ElrslyO0C3MqUThJAv3bm2CZgaeUhzRzs4mioCQXizqZguZqFU06qsEpAlSmYKVguZ+CdTao7SkCrqLYpWOrT6NZSarESkIlWmYLlIg3vdDycgLvQZ1Ow1Cbwvh8PNVAX/JCYgrvnSXTWhvuTqTnwQ2ICdg5i/TlgfSfRD8kgcGQSWWySmSGhz7SKalMw7syxeR8J/lncjQJR5b//RsvqAc7BZW2fkre1AAAAAElFTkSuQmCC",

              : Index=>1,

              : Type=>"TrafficLights31"

            },

            {

              : ImageData=>"iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAFQSURBVDhPtZNNSwJhFIXnl7R22yoyaCFJ5GQLJShCashgMskkQZSkwUAQCkEswYXgouhjGfYhRVop5br/c/LcJiZpyHfT3Qzzzvsc7j33jPYvddk+w87xJnwpLzxrY/LkO8/tK+7V/XiBWTIwV9RhnMaQbOWR6R0hfreHpcY6fAW/fOc9G3GKh2FLR/Q8AatfQe69jOxbCeneIXa7RSReC4g/HyDUWJV7v0SoPAo2OxaiTzkE6yvSiY1+zcy2VWDjMYvIQxqT+WnHExrEmVXh5VYKM7WwGCsCdJmGqcKL90nMXw1MHXAiwFXRbVU4dLuNYDMmKxYBKnFVqvDCzRb8FxGnA87CPavCgaaJqRPd8YBuMiSq8Oz1Bsb3J4aTyb0yJCqwt6oP54D1nUSGZBTsmkQWD6nMkHDPXBXdpmGcmW3zuyv8szgbDaLLf/+NmvYJNYboi7zW2bMAAAAASUVORK5CYII=",

              : Index=>2,

              : Type=>"TrafficLights31"

            }

          ],

          : Cfvos=>[

            {

              : IsGTE=>false,

              : Type=>"Percent",

              : Value=>"0"

            },

            {

              : IsGTE=>false,

              : Type=>"Percent",

              : Value=>"33"

            },

            {

              : IsGTE=>false,

              : Type=>"Percent",

              : Value=>"67"

            }

          ],

          : IsCustom=>false,

          : Reverse=>false,

          : ShowValue=>false,

          : IconSetType=>"CustomSet"

        },

        : Style=>{

          : Font=>{

            : Color=>{

              : A=>"255",

              : R=>"0",

              : G=>"0",

              : B=>"0"

            },

            : DoubleSize=>11.0,

            : IsBold=>false,

            : IsItalic=>false,

            : IsStrikeout=>false,

            : IsSubscript=>false,

            : IsSuperscript=>false,

            : Name=>"宋体",

            : Size=>11,

            : Underline=>"None"

          },

          : Custom=>"",

          : BackgroundColor=>{

            : A=>"0",

            : R=>"0",

            : G=>"0",

            : B=>"0"

          },

          : ForegroundColor=>{

            : A=>"0",

            : R=>"0",

            : G=>"0",

            : B=>"0"

          },

          : IsFormulaHidden=>false,

          : IsDateTime=>false,

          : IsTextWrapped=>false,

          : IsGradient=>false,

          : IsLocked=>false,

          : IsPercent=>false,

          : ShrinkToFit=>false,

          : IndentLevel=>0,

          : Number=>0,

          : RotationAngle=>0,

          : Pattern=>"None",

          : TextDirection=>"Context",

          : VerticalAlignment=>"Center",

          : HorizontalAlignment=>"General",

          : BorderCollection=>[

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"BottomBorder"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"DiagonalDown"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"DiagonalUp"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"Horizontal"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"LeftBorder"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"RightBorder"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"TopBorder"

            },

            {

              : LineStyle=>"None",

              : Color=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : BorderType=>"Vertical"

            }

          ]

        },

        : link=>{

          : Href=>"/0",

          : Rel=>"self"

        }

      }

    ],

    : link=>{

      : Href=>"http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet1/conditionalformattings/0",

      : Rel=>"self"

    }

  },

  : Code=>"200",

  : Status=>"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Python" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}



{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-ConditionalFormatting-GetConditionalFormatting-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-cells-get-conditional-formatting-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}



{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-ConditionalFormatting-get\_worksheet\_conditional\_formatting-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}



{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-ConditionalFormatting-GetConditionalFormatting-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}



{{< /tab >}}

{{< tab tabNum="7" >}}



{{< /tab >}}

{{< tab tabNum="8" >}}



{{< /tab >}}

{{< tab tabNum="9" >}}



{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-ConditionalFormatting-GetConditionalFormatting-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}



{{< gist "aspose-cloud" "d1809f85075aaa2f4d954930e916d115" >}}

{{< /tab >}}

{{< /tabs >}}
