---
title: "Calculate All Formulas in a Workbook"
type: docs
url: /calculate-all-formulas-in-a-workbook/
weight: 140
---

## **Introduction**
This example shows how to calculate all formulas in a workbook using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/cells/{name}/calculateformula|POST|Calculate Formula|[PostWorkbookCalculateFormula](https://apireference.aspose.cloud/cells/#/Workbook/PostWorkbookCalculateFormula)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/calculateformula?ignoreError=true" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"CalcStackSize\": 1, \"IgnoreError\": true, \"PrecisionStrategy\": \"string\", \"Recursive\": true}"

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
{{< tabs tabTotal="7" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Node.js" tabName5="Perl" tabName6="Go" tabName7="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "f21c488545888fe78bbd97e47790246b" "Examples-.NET-CellsWorkbookPostWorkbookCalculateFormula.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostWorkbookCalculateFormula-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-post_workbook_calculate_formula-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Workbook-PostWorkbookCalculateFormula-1.js" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Workbook-CalculateFormulas-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "92c0f4d6c417e88e16cce17e10dd3287" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "2a8718092583a1d495bac5034f80a503" >}}

{{< /tab >}}

{{< /tabs >}}
