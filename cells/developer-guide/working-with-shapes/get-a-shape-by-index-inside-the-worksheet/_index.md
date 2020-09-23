---
title: "Get a Shape by Index inside the Worksheet"
type: docs
url: /get-a-shape-by-index-inside-the-worksheet/
weight: 20
---

## **Introduction**
This example shows how to get a shape by index inside the worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/shapes/{shapeindex}|GET|Get a shape description in worksheet|[GetWorksheetShape](https://apireference.aspose.cloud/cells/#/Shapes/GetWorksheetShape)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/shapes/0" -H "accept: application/json" 
-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Status": "string",

  "Shape": {

    "link": {

      "Href": "string",

      "Rel": "string",

      "Title": "string",

      "Type": "string"

    },

    "Name": "string",

    "MsoDrawingType": "string",

    "AutoShapeType": "string",

    "Placement": "string",

    "UpperLeftRow": 0,

    "Top": 0,

    "UpperLeftColumn": 0,

    "Left": 0,

    "LowerRightRow": 0,

    "Bottom": 0,

    "LowerRightColumn": 0,

    "Right": 0,

    "Width": 0,

    "Height": 0,

    "X": 0,

    "Y": 0,

    "RotationAngle": 0,

    "HtmlText": "string",

    "Text": "string",

    "AlternativeText": "string",

    "TextHorizontalAlignment": "string",

    "TextHorizontalOverflow": "string",

    "TextOrientationType": "string",

    "TextVerticalAlignment": "string",

    "TextVerticalOverflow": "string",

    "IsGroup": true,

    "IsHidden": true,

    "IsLockAspectRatio": true,

    "IsLocked": true,

    "IsPrintable": true,

    "IsTextWrapped": true,

    "IsWordArt": true,

    "LinkedCell": "string",

    "ZOrderPosition": 0

  }

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="VB.NET" tabName3="Java" tabName4="Go" >}}

{{< tab tabNum="1" >}}

```java

//Please upload sampleShapes.xlsx file in the cloud storage.

//The following url will get 4th shape inside the Sheet1.

string url = "http://api.aspose.com/v3.0/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes/3";

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

'The following url will get 4th shape inside the Sheet1.

Dim url As String = "http://api.aspose.com/v3.0/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes/3"

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

//The following url will get 4th shape inside the Sheet1.

String url = "http://api.aspose.com/v3.0/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes/3";

//Sign the url with your AppSID and AppKey.

String signedURL = Sign(url, m_AppSID, m_AppKey);

//Call process command with the signed URL.

InputStream responseStream = ProcessCommand(signedURL, "GET");

//Convert response stream into string.

```

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "dd6d8ac9aacd9be6085356c07dbbadd0" >}}

{{< /tab >}}

{{< /tabs >}}

