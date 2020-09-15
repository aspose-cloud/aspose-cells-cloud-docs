---
title: "Add a Shape inside the Worksheet"
type: docs
url: /add-a-shape-inside-the-worksheet/
weight: 30
---

## **Introduction**
This example shows how to add a shape inside the worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/shapes|PUT|Adds shape in worksheet|[PutWorksheetShape](https://apireference.aspose.cloud/cells/#/Shapes/PutWorksheetShape)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/shapes?DrawingType=arc&upperLeftRow=1&upperLeftColumn=1&top=1&left=1&width=100&height=100" 

-H "accept: application/json" 

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
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="VB.NET" tabName3="Java" tabName4="Go" >}}

{{< tab tabNum="1" >}}

```java

//Please upload sample.xlsx file in the cloud storage.

//The following url will add Arc shape inside the Sheet1.

string url = "http://api.aspose.com/v3.0/cells/sample.xlsx/worksheets/Sheet1/shapes?DrawingType=Arc&upperLeftRow=2&upperLeftColumn=3&top=0&left=0&width=100&height=100";

//Sign the url with your AppSID and AppKey.

string signedURL = Sign(url, m\_AppSID, m\_AppKey);

//Call process command with the signed URL.

Stream responseStream = ProcessCommand(signedURL, "PUT");

//Convert response stream into string.

//Download sample.xlsx file from cloud storage to view the added shape.

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

'Please upload sample.xlsx file in the cloud storage.

'The following url will add Arc shape inside the Sheet1.

Dim url As String = "http://api.aspose.com/v3.0/cells/sample.xlsx/worksheets/Sheet1/shapes?DrawingType=Arc&upperLeftRow=2&upperLeftColumn=3&top=0&left=0&width=100&height=100"

'Sign the url with your AppSID and AppKey.

Dim signedURL As String = Sign(url, m\_AppSID, m\_AppKey)

'Call process command with the signed URL.

Dim responseStream As Stream = ProcessCommand(signedURL, "PUT")

'Convert response stream into string.

'Download sample.xlsx file from cloud storage to view the added shape.

```

{{< /tab >}}

{{< tab tabNum="3" >}}

```java

//Please upload sample.xlsx file in the cloud storage.

//The following url will add Arc shape inside the Sheet1.

String url = "http://api.aspose.com/v3.0/cells/sample.xlsx/worksheets/Sheet1/shapes?DrawingType=Arc&upperLeftRow=2&upperLeftColumn=3&top=0&left=0&width=100&height=100";

//Sign the url with your AppSID and AppKey.

String signedURL = Sign(url, m\_AppSID, m\_AppKey);

//Call process command with the signed URL.

InputStream responseStream = ProcessCommand(signedURL, "PUT");

//Convert response stream into string.

//Download sample.xlsx file from cloud storage to view the added shape.

```

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "34f478cae8c02848db0e376bd592a087" >}}

{{< /tab >}}

{{< /tabs >}}
