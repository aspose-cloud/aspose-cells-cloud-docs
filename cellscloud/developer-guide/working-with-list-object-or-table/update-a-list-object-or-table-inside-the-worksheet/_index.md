---
title: "Update a List Object or Table inside the Worksheet"
type: docs
url: /update-a-list-object-or-table-inside-the-worksheet/
weight: 20
---

## **Introduction**
This example shows how to update a list object or table inside the worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/listobjects/{listObjectIndex}|POST|Updates list object in worksheet|[PostWorksheetListObject](https://apireference.aspose.cloud/cells/#/ListObjects/PostWorksheetListObject)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/listobjects/0" 

-d "{

     "link":  {

         "Href":  "string",

         "Rel":  "string",

         "Title":  "string",

         "Type":  "string" 

    },

     "AutoFilter":  {

         "link":  {

             "Href":  "string",

             "Rel":  "string",

             "Title":  "string",

             "Type":  "string" 

        },

         "FilterColumns":  [

             {

                 "FieldIndex":  0,

                 "FilterType":  "string",

                 "MultipleFilters":  {

                     "MatchBlank":  true,

                     "MultipleFilterList":  [

                         {



                        } 

                    ] 

                },

                 "ColorFilter":  {

                     "FilterByFillColor":  "string",

                     "Pattern":  "string",

                     "Color":  {

                         "Color":  {

                             "A":  0,

                             "R":  0,

                             "G":  0,

                             "B":  0 

                        },

                         "ColorIndex":  0,

                         "IsShapeColor":  true,

                         "ThemeColor":  {

                             "ColorType":  "string",

                             "Tint":  0 

                        },

                         "Type":  "string" 

                    },

                     "ForegroundColorColor":  {

                         "Color":  {

                             "A":  0,

                             "R":  0,

                             "G":  0,

                             "B":  0 

                        },

                         "ColorIndex":  0,

                         "IsShapeColor":  true,

                         "ThemeColor":  {

                             "ColorType":  "string",

                             "Tint":  0 

                        },

                         "Type":  "string" 

                    },

                     "BackgroundColor":  {

                         "Color":  {

                             "A":  0,

                             "R":  0,

                             "G":  0,

                             "B":  0 

                        },

                         "ColorIndex":  0,

                         "IsShapeColor":  true,

                         "ThemeColor":  {

                             "ColorType":  "string",

                             "Tint":  0 

                        },

                         "Type":  "string" 

                    } 

                },

                 "CustomFilters":  [

                     {

                         "FilterOperatorType":  "string" 

                    } 

                ],

                 "DynamicFilter":  {

                     "DynamicFilterType":  "string" 

                },

                 "IconFilter":  {

                     "IconId":  0,

                     "IconSetType":  "string" 

                },

                 "Top10Filter":  {

                     "Criteria":  "string",

                     "IsPercent":  true,

                     "IsTop":  true,

                     "Items":  0 

                },

                 "Visibledropdown":  "string" 

            } 

        ],

         "Range":  "string",

         "Sorter":  {

             "CaseSensitive":  true,

             "HasHeaders":  true,

             "KeyList":  [

                 {

                     "Key":  0,

                     "SortOrder":  "string",

                     "CustomList":  "string" 

                } 

            ],

             "SortLeftToRight":  true 

        } 

    },

     "DisplayName":  "string",

     "StartColumn":  0,

     "StartRow":  0,

     "EndColumn":  0,

     "EndRow":  0,

     "ListColumns":  [

         {

             "Name":  "string",

             "TotalsCalculation":  "string" 

        } 

    ],

     "ShowHeaderRow":  true,

     "ShowTableStyleColumnStripes":  true,

     "ShowTableStyleFirstColumn":  true,

     "ShowTableStyleLastColumn":  true,

     "ShowTableStyleRowStripes":  true,

     "ShowTotals":  true,

     "TableStyleName":  "string",

     "TableStyleType":  "string"

}" 

-H "accept: application/json" 

-H "Content-Type: application/json" 

-H "x-aspose-client: Containerize.Swagger" 

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

   "Code": "OK",

   "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="VB.NET" tabName3="Java" tabName4="Go" >}}

{{< tab tabNum="1" >}}

```java

//Please upload sample.xlsx file in the cloud storage.

//Sign ListObject API with your AppSID and AppKey

//The URL updates the first list object or table inside the Sheet1 of workbook

string strURI = "http://api.aspose.com/v3.0/cells/sample.xlsx/worksheets/Sheet1/listobjects/0";

strURI = Sign(strURI, m\_AppSID, m\_AppKey);

//XML body that updates the end row, end column and style of list object or table

string xmlBody = @"

<ListObject>

   <EndRow>26</EndRow>

   <EndColumn>12</EndColumn>

   <TableStyleName>TableStyleMedium10</TableStyleName>

   <TableStyleType>TableStyleMedium10</TableStyleType>

</ListObject>";

//Call Process Command with Signed URI

Stream responseStream = ProcessCommand(strURI, "POST", xmlBody, "XML");

//Convert response stream into string

//Please download sample.xlsx file from the cloud storage.

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

'Please upload sample.xlsx file in the cloud storage.

'Sign ListObject API with your AppSID and AppKey

'The URL updates the first list object or table inside the Sheet1 of workbook

Dim strURI As String = "http://api.aspose.com/v3.0/cells/sample.xlsx/worksheets/Sheet1/listobjects/0"

strURI = Sign(strURI, m\_AppSID, m\_AppKey)

'XML body that updates the end row, end column and style of list object or table

Dim xmlBody As String = "<ListObject><EndRow>26</EndRow><EndColumn>12</EndColumn><TableStyleName>TableStyleMedium10</TableStyleName><TableStyleType>TableStyleMedium10</TableStyleType></ListObject>"

'Call Process Command with Signed URI

Dim responseStream As Stream = ProcessCommand(strURI, "POST", xmlBody, "XML")

'Convert response stream into string

'Please download sample.xlsx file from the cloud storage.

```

{{< /tab >}}

{{< tab tabNum="3" >}}

```java

//Please upload sample.xlsx file in the cloud storage.

//Sign ListObject API with your AppSID and AppKey

//The URL updates the first list object or table inside the Sheet1 of workbook

String strURI = "http://api.aspose.com/v3.0/cells/sample.xlsx/worksheets/Sheet1/listobjects/0";

strURI = Sign(strURI, m\_AppSID, m\_AppKey);

//XML body that updates the end row, end column and style of list object or table

String xmlBody = "<ListObject><EndRow>26</EndRow><EndColumn>12</EndColumn><TableStyleName>TableStyleMedium10</TableStyleName><TableStyleType>TableStyleMedium10</TableStyleType></ListObject>";

//Call Process Command with Signed URI

InputStream responseStream = ProcessCommand(strURI, "POST", xmlBody, "XML");

//Convert response stream into string

//Please download sample.xlsx file from the cloud storage.

```

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< /tab >}}

{{< /tabs >}}
