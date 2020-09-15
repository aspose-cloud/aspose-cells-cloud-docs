---
title: "Apply Rich Text Formatting to a Cell"
type: docs
url: /apply-rich-text-formatting-to-a-cell/
weight: 40
---

## **Introduction**
This example shows how to apply Rich Text Formatting to a Cell using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/cells/A1/characters?appSid=xxxx&signature=xxxx" \

     -d '{

          "FontSetting": [

            {

              "Font": {

                "IsBold": "true",

                "Size": "24"

              },

              "Length": "5",

              "StartIndex": "0"

            },

            {

              "Font": {

                "IsItalic": "true",

                "Size": "15"

              },

              "Length": "4",

              "StartIndex": "5"

            }

          ]

        }'    

     -X POST \

     -H "Content-Type: application/json" \

     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Node.js" tabName5="Perl" tabName6="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-Cells-ApplyRichTextFormatting-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Cells-PostCellTextFormatting-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Cells-post\_cell\_text\_formatting-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Cells-ApplyRichTextFormatting-1.js" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Cells-ApplyRichTextFormatting-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "9decd80776653e876bf47e2cfb298eee" >}}

{{< /tab >}}

{{< /tabs >}}
