---
title: "Get Text Items from a Worksheet"
type: docs
url: /get-text-items-from-a-worksheet/
weight: 20
---

## **Introduction**
This example shows how to read TextItem information from a sheet in a Excel Workbook using Aspose.Cells Cloud API.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/textItems|GET|Read TextItems from a Excel Worksheet|[GetWorkSheetTextItems](https://apireference.aspose.cloud/cells/#/Worksheets/GetWorkSheetTextItems)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/test.xlsx/worksheets/sheet1/textItems" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1Njk2OTg3NzcsImV4cCI6MTU2OTc4NTE3NywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.cTT1ew15ns0DFsstBkOidtlQcQsQMrlbOoA0kH1rA7R6kUbgwrHbC\_Us1AN5xsHe8Gb8R\_y8sSbDenm3xJkkSWSNXzOB7zr7HhK79sp-vUyfXkx8MCXFDlXdysNGT6ifZCag45PUgG-PQAnB2bpgrTQu8vIHyue5Iz4Wl9o\_FfTGlPsqNEQRXFY39mpsGD6jp0b2B-J3NI4fNwLILRs3GRX273\_5BCmAEf4o8Q72a1IlRzrGZK20gZ6V4\_CLUdMIG3CeE6Uojx97iLA7BpTFq4UdbMCLMTeexV1mWPdQ\_dMZ5zRsdIJVfvT169yx81P3gMeMSOBUv4\_Su9BO6KVqEw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "TextItems": {

    "TextItemList": [

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "a12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M1",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "1",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N2",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N3",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N4",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N5",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N6",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N7",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N8",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N9",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N10",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N11",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N12",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N13",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N14",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N15",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "15",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N16",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "16",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N17",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "17",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/A18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "2",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/B18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "3",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/C18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "4",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/D18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "5",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/E18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "6",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/F18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "7",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/G18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "8",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/H18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "9",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/I18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "10",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/J18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "11",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/K18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "12",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/L18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "13",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/M18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      },

      {

        "Text": "14",

        "link": {

          "Href": "/test.xlsx/worksheets/sheet1/cells/N18",

          "Rel": "parent",

          "Title": null,

          "Type": null

        }

      }

    ],

    "link": {

      "Href": "/test.xlsx/worksheets/sheet1/textitems",

      "Rel": "self",

      "Title": null,

      "Type": null

    }

  },

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Text-GetTextItemWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-text-GetTextItemWorksheet-get-text-item-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Text-GetWorkSheetTextItems-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Worksheet-get\_worksheet\_text\_items-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "GetTextITemsFromWorkSheet.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Text-GetTextItemWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-text-GetTextItemWorksheet-get-text-item-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Text-GetTextItemWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< /tab >}}

{{< /tabs >}}
