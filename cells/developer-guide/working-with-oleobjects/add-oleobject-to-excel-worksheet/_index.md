---
title: "Add OleObject to Excel Worksheet"
type: docs
url: /add-oleobject-to-excel-worksheet/
weight: 20
---

## **Introduction**
This example shows how to add an OleObject to a worksheet using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/oleobjects|PUT|Add an OLE object in worksheet|[PutWorksheetOleObject](https://apireference.aspose.cloud/cells/#/OleObjects/PutWorksheetOleObject)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.com/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1/oleobjects?appSID=xxxx&signature=xxxx" \
     -X PUT \
     -d '{"ImageSourceFullName":"aspose-logo.png", "IsAutoSize":true, "SourceFullName":"Sample_Book2.xls", "UpperLeftRow":15, "Top":10, "UpperLeftColumn":5, "Left":10,"Width":400, "Height":400}' \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "OleObject": {

    "DisplayAsIcon": false,

    "FileFormatType": "Default",

    "ImageSourceFullName": "aspose-logo.png",

    "IsAutoSize": false,

    "IsLink": false,

    "ProgID": "Excel.Sheet.8",

    "SourceFullName": "Sample_Book2.xls",

    "Name": "OleObject 1",

    "MsoDrawingType": "OleObject",

    "AutoShapeType": "PictureFrame",

    "Placement": "Move",

    "UpperLeftRow": 15,

    "Top": 10,

    "UpperLeftColumn": 5,

    "Left": 10,

    "LowerRightRow": 39,

    "Bottom": 2,

    "LowerRightColumn": 11,

    "Right": 26,

    "Width": 400,

    "Height": 400,

    "X": 330,

    "Y": 275,

    "RotationAngle": 0.0,

    "AlternativeText": "",

    "TextHorizontalAlignment": "Left",

    "TextHorizontalOverflow": "Overflow",

    "TextOrientationType": "NoRotation",

    "TextVerticalOverflow": "Overflow",

    "IsGroup": false,

    "IsHidden": false,

    "IsLockAspectRatio": false,

    "IsLocked": false,

    "IsPrintable": false,

    "IsTextWrapped": false,

    "IsWordArt": false,

    "ZOrderPosition": 0,

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1/oleobjects/0",

      "Rel": "self"

    }

  },

  "Code": "200",

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Python" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-OleObjects-AddOleObjectsWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-oleobjects-AddOleObjectsWorksheet-add-ole-objects-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-OLEObjects-PutWorksheetOleObject-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-OLEObject-add_ole_object-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Oleobjects-AddOleObjectsWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "AddOLEObjectsToExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-oleobjects-AddOleObjectsWorksheet-add-ole-objects-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Oleobjects-AddOleObjectsWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "9c929ad7c5fe5078d6f5532dff537058" >}}

{{< /tab >}}

{{< /tabs >}}
