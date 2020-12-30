---
title: "Sort Table Data"
type: docs
url: /sort-table-data/
weight: 40
---

## **Introduction**
This example shows how to sort table's data using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/listobjects/{listObjectIndex}/sort|POST|Sorts list object in worksheet|[PostWorksheetListObjectSortTable](https://apireference.aspose.cloud/cells/#/ListObjects/PostWorksheetListObjectSortTable)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/sheet7/listobjects/1/sort" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"CaseSensitive\": true, \"HasHeaders\": true, \"KeyList\": [ { \"Key\": 1, \"SortOrder\": \"Ascending\", \"CustomList\": \"string\" } ], \"SortLeftToRight\": true}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

	"Code":200,

	"Status":"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Node.js" tabName5="Perl" tabName6="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNet-CSharp-Table-SortTableData-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-ListObjects-PostSortTableData-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-ListObjects-post_sort_table_data-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Table-SortTableData-1.js" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Table-SortTableData-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "337292f6bcf5db7e7a0bea74f355071a" >}}

{{< /tab >}}

{{< /tabs >}}
