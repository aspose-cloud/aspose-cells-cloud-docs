---
title: "Get Conditional Formattings of Worksheet"
type: docs
url: /get-conditional-formattings-of-worksheet/
weight: 10
---

## **Introduction**
This example shows how to get conditional formatting of worksheet detail information using Aspose.Cells Cloud API. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/conditionalFormattings|GET|Get conditional formattings description|[GetWorksheetConditionalFormattings](https://apireference.aspose.cloud/cells/#/ConditionalFormattings/GetWorksheetConditionalFormattings)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet1/conditionalFormattings?appSID=xxxx&signature=xxxx" \
-X GET \
-H "Content-Type: application/json" \
-H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  : ConditionalFormattings=>{

    : Count=>5,

    : ConditionalFormattingList=>[

      {

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

          : Href=>"/0",

          : Rel=>"self"

        }

      },

      {

        : sqref=>"G15:I19 K20:L21 ",

        : FormatConditions=>[

          {

            : Priority=>4,

            : Type=>"CellValue",

            : StopIfTrue=>false,

            : Formula1=>"=\"w\"",

            : Operator=>"LessThan",

            : Style=>{

              : Font=>{

                : Color=>{

                  : A=>"255",

                  : R=>"156",

                  : G=>"0",

                  : B=>"6"

                },

                : DoubleSize=>10.0,

                : IsBold=>false,

                : IsItalic=>false,

                : IsStrikeout=>false,

                : IsSubscript=>false,

                : IsSuperscript=>false,

                : Name=>"Arial",

                : Size=>10,

                : Underline=>"None"

              },

              : Custom=>"",

              : BackgroundColor=>{

                : A=>"255",

                : R=>"255",

                : G=>"199",

                : B=>"206"

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

          },

          {

            : Priority=>5,

            : Type=>"CellValue",

            : StopIfTrue=>false,

            : Formula1=>"1",

            : Operator=>"GreaterThan",

            : Style=>{

              : Font=>{

                : Color=>{

                  : A=>"255",

                  : R=>"156",

                  : G=>"0",

                  : B=>"6"

                },

                : DoubleSize=>10.0,

                : IsBold=>false,

                : IsItalic=>false,

                : IsStrikeout=>false,

                : IsSubscript=>false,

                : IsSuperscript=>false,

                : Name=>"Arial",

                : Size=>10,

                : Underline=>"None"

              },

              : Custom=>"",

              : BackgroundColor=>{

                : A=>"255",

                : R=>"255",

                : G=>"199",

                : B=>"206"

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

              : Href=>"/1",

              : Rel=>"self"

            }

          }

        ],

        : link=>{

          : Href=>"/1",

          : Rel=>"self"

        }

      },

      {

        : sqref=>"D30:G34 I34:J35 M35 L35:L36 L38 J41 F41 ",

        : FormatConditions=>[

          {

            : Priority=>3,

            : Type=>"DataBar",

            : StopIfTrue=>false,

            : DataBar=>{

              : AxisColor=>{

                : A=>"255",

                : R=>"0",

                : G=>"0",

                : B=>"0"

              },

              : AxisPosition=>"Automatic",

              : BarBorder=>{

                : Color=>{

                  : A=>"255",

                  : R=>"99",

                  : G=>"195",

                  : B=>"132"

                },

                : Type=>"DataBarBorderSolid"

              },

              : BarFillType=>"DataBarFillGradient",

              : Color=>{

                : A=>"255",

                : R=>"99",

                : G=>"195",

                : B=>"132"

              },

              : Direction=>"Context",

              : MaxCfvo=>{

                : IsGTE=>false,

                : Type=>"AutomaticMax"

              },

              : MaxLength=>100,

              : MinCfvo=>{

                : IsGTE=>false,

                : Type=>"AutomaticMin"

              },

              : MinLength=>0,

              : NegativeBarFormat=>{

                : BorderColor=>{

                  : A=>"255",

                  : R=>"255",

                  : G=>"0",

                  : B=>"0"

                },

                : BorderColorType=>"DataBarColor",

                : Color=>{

                  : A=>"255",

                  : R=>"255",

                  : G=>"0",

                  : B=>"0"

                },

                : ColorType=>"DataBarColor"

              },

              : ShowValue=>false

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

          : Href=>"/2",

          : Rel=>"self"

        }

      },

      {

        : sqref=>"D30:G34 I34:J35 M35 L35:L36 L38 J41 F41 ",

        : FormatConditions=>[

          {

            : Priority=>2,

            : Type=>"ColorScale",

            : StopIfTrue=>false,

            : ColorScale=>{

              : MaxCfvo=>{

                : IsGTE=>false,

                : Type=>"Max"

              },

              : MaxColor=>{

                : A=>"255",

                : R=>"248",

                : G=>"105",

                : B=>"107"

              },

              : MidCfvo=>{

                : IsGTE=>false,

                : Type=>"Percentile",

                : Value=>"50"

              },

              : MidColor=>{

                : A=>"255",

                : R=>"252",

                : G=>"252",

                : B=>"255"

              },

              : MinCfvo=>{

                : IsGTE=>false,

                : Type=>"Min"

              },

              : MinColor=>{

                : A=>"255",

                : R=>"90",

                : G=>"138",

                : B=>"198"

              }

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

          : Href=>"/3",

          : Rel=>"self"

        }

      },

      {

        : sqref=>"D30:G34 I34:J35 M35 L35:L36 L38 J41 F41 ",

        : FormatConditions=>[

          {

            : Priority=>1,

            : Type=>"Top10",

            : StopIfTrue=>false,

            : Style=>{

              : Font=>{

                : Color=>{

                  : A=>"255",

                  : R=>"156",

                  : G=>"0",

                  : B=>"6"

                },

                : DoubleSize=>10.0,

                : IsBold=>false,

                : IsItalic=>false,

                : IsStrikeout=>false,

                : IsSubscript=>false,

                : IsSuperscript=>false,

                : Name=>"Arial",

                : Size=>10,

                : Underline=>"None"

              },

              : Custom=>"",

              : BackgroundColor=>{

                : A=>"255",

                : R=>"255",

                : G=>"199",

                : B=>"206"

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

            : Top10=>{

              : IsBottom=>false,

              : IsPercent=>false,

              : Rank=>10

            },

            : link=>{

              : Href=>"/0",

              : Rel=>"self"

            }

          }

        ],

        : link=>{

          : Href=>"/4",

          : Rel=>"self"

        }

      }

    ],

    : link=>{

      : Href=>"http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet1/conditionalformattings",

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



{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-ConditionalFormatting-GetWorksheetConditionalFormatting-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-cells-get-conditional-formatting-worksheet.java" >}}



{{< /tab >}}

{{< tab tabNum="3" >}}



{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-ConditionalFormatting-get\_worksheet\_conditional\_formattings-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}



{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-ConditionalFormatting-GetWorksheetConditionalFormatting-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}



{{< /tab >}}

{{< tab tabNum="7" >}}



{{< /tab >}}

{{< tab tabNum="8" >}}



{{< /tab >}}

{{< tab tabNum="9" >}}



{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-ConditionalFormatting-GetWorksheetConditionalFormatting-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "b2a10009556f14d1f939a8433925c5f6" >}}

{{< /tab >}}

{{< /tabs >}}
