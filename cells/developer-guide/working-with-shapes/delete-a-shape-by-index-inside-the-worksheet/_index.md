---
title: "Delete a Shape by Index inside the Worksheet"
type: docs
url: /delete-a-shape-by-index-inside-the-worksheet/
weight: 50
---

## **Introduction**
This example shows how to delete a shape by index inside the worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/shapes/{shapeindex}|DELETE|Delete a shape in worksheet|[DeleteWorksheetShape](https://apireference.aspose.cloud/cells/#/Shapes/DeleteWorksheetShape)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/cells/Book1.xlsx/worksheets/Sheet1/shapes/1" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

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

//The following url will delete 4th shape inside the Sheet1.

string url = "http://api.aspose.com/v3.0/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes/3";

//Sign the url with your AppSID and AppKey.

string signedURL = Sign(url, m_AppSID, m_AppKey);

//Call process command with the signed URL.

Stream responseStream = ProcessCommand(signedURL, "DELETE");

//Convert response stream into string.

//Download sampleShapes.xlsx file from cloud storage.

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

'Please upload sampleShapes.xlsx file in the cloud storage.

'The following url will delete 4th shape inside the Sheet1.

Dim url As String = "http://api.aspose.com/v3.0/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes/3"

'Sign the url with your AppSID and AppKey.

Dim signedURL As String = Sign(url, m_AppSID, m_AppKey)

'Call process command with the signed URL.

Dim responseStream As Stream = ProcessCommand(signedURL, "DELETE")

'Convert response stream into string.

'Download sampleShapes.xlsx file from cloud storage.

```

{{< /tab >}}

{{< tab tabNum="3" >}}

```java

//Please upload sampleShapes.xlsx file in the cloud storage.

//The following url will delete 4th shape inside the Sheet1.

String url = "http://api.aspose.com/v3.0/cells/sampleShapes.xlsx/worksheets/Sheet1/shapes/3";

//Sign the url with your AppSID and AppKey.

String signedURL = Sign(url, m_AppSID, m_AppKey);

//Call process command with the signed URL.

InputStream responseStream = ProcessCommand(signedURL, "DELETE");

//Convert response stream into string.

//Download sampleShapes.xlsx file from cloud storage.

```

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "146761753dfc29a19e41a7de616c9d2c" >}}

{{< /tab >}}

{{< /tabs >}}
