---
title: "Get all Shapes inside the Worksheet"
type: docs
url: /get-all-shapes-inside-the-worksheet/
weight: 10
---

## **Introduction**
This example shows how to get all shapes inside the worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/shapes|GET|Get shapes description in worksheet|[GetWorksheetShapes](https://apireference.aspose.cloud/cells/#/Shapes/GetWorksheetShapes)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/shapes" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Shapes" : {

    "ShapeList" : [

      {

        "link" : {

          "Href" : "/0",

          "Rel" : "self",

          "Type" : null,

          "Title" : null

        }

      },

      {

        "link" : {

          "Href" : "/1",

          "Rel" : "self",

          "Type" : null,

          "Title" : null

        }

      },

      {

        "link" : {

          "Href" : "/2",

          "Rel" : "self",

          "Type" : null,

          "Title" : null

        }

      },

      {

        "link" : {

          "Href" : "/3",

          "Rel" : "self",

          "Type" : null,

          "Title" : null

        }

      }

    ],

    "link" : {

      "Href" : "http://api.aspose.com/v1.1/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes",

      "Rel" : "self",

      "Type" : null,

      "Title" : null

    }

  },

  "Code" : 200,

  "Status" : "OK"

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

//Please upload sampleShapes.xlsx file in the cloud storage.

//The following url will retrieve all the shapes from the Sheet1.

string url = "http://api.aspose.com/v1.1/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes";

//Sign the url with your AppSID and AppKey.

string signedURL = Sign(url, m_AppSID, m_AppKey);

//Call process command with the signed URL.

Stream responseStream = ProcessCommand(signedURL, "GET");

//Convert response stream into string.

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

'Please upload sampleShapes.xlsx file in the cloud storage.

'The following url will retrieve all the shapes from the Sheet1

Dim url As String = "http://api.aspose.com/v1.1/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes"

'Sign the url with your AppSID and AppKey.

Dim signedURL As String = Sign(url, m_AppSID, m_AppKey)

'Call process command with the signed URL.

Dim responseStream As Stream = ProcessCommand(signedURL, "GET")

'Convert response stream into string.

```

{{< /tab >}}

{{< tab tabNum="3" >}}

```java

//Please upload sampleShapes.xlsx file in the cloud storage.

//The following url will retrieve all the shapes from the Sheet1.

String url = "http://api.aspose.com/v1.1/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes";

//Sign the url with your AppSID and AppKey.

String signedURL = Sign(url, m_AppSID, m_AppKey);

//Call process command with the signed URL.

InputStream responseStream = ProcessCommand(signedURL, "GET");

//Convert response stream into string.

```

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "2118580a8c2f08f37269d89ff9f57781" >}}

{{< /tab >}}

{{< /tabs >}}
