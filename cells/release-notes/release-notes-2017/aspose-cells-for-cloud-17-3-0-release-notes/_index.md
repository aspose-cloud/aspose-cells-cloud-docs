---
title: "Aspose.Cells for Cloud 17.3.0 Release Notes"
type: docs
url: /aspose-cells-for-cloud-17-3-0-release-notes/
weight: 80
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Cells for Cloud 17.3.0](https://downloads.aspose.com/cells/cloud/new-releases/aspose.cells-for-cloud-17.3.0/).

{{% /alert %}} 

|**Key**|**Summary**|**Category**|
| :- | :- | :- |
|CELLSCLOUD-10028|Insert page breaks in Excel worksheet|New Feature|
|CELLSCLOUD-10035|Support AutoFit row heights|New Feature|
|CELLSCLOUD-10036|Support AutoFit columns' width|New Feature|
#### **Get Horizontal Page Breaks inside Worksheet**
The following sample code illustrates how to get Horizontal Page Breaks inside Worksheet using Aspose.Cells for Cloud API.

```java

//Your workbook and sheet name

string workbookName = "sampleExcelPageBreaks.xlsx";

string sheetName = "Sheet1";



//URL to Get Horizontal Page Breaks

string url = "http://api.aspose.com/v1.1/cells/"+ workbookName + "/worksheets/" + sheetName + "/horizontalpagebreaks";



//Call Get method with the following parameters

string data = "";

string contentType = "application/json";

using (HttpWebResponse response = \_helper.CallGet(url, data, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **Get Vertical Page Breaks inside Worksheet**
The following sample code illustrates how to get Vertical Page Breaks inside Worksheet using Aspose.Cells for Cloud API.

```java

//Your workbook and sheet name

string workbookName = "sampleExcelPageBreaks.xlsx";

string sheetName = "Sheet1";



//URL to Get Horizontal Page Breaks

string url = "http://api.aspose.com/v1.1/cells/"+ workbookName + "/worksheets/" + sheetName + "/verticalpagebreaks";



//Call Get method with the following parameters

string data = "";

string contentType = "application/json";

using (HttpWebResponse response = \_helper.CallGet(url, data, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **Insert Horizontal Page Break inside Worksheet**
The following sample code illustrates how to insert Horizontal Page Break inside Worksheet using Aspose.Cells for Cloud API.

```java

//Your workbook and sheet name

string workbookName = "sampleExcelPageBreaks.xlsx";

string sheetName = "Sheet1";



//Row index to insert horizontal page break

int idxRow = 18;



//URL to insert horizontal page break

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/horizontalpagebreaks?row=" + idxRow;



//Call PUT method with the following parameters

string data = "";

string contentType = "application/json";

using (HttpWebResponse response = \_helper.CallPut(url, data, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **Insert Vertical Page Break inside Worksheet**
The following sample code illustrates how to insert Vertical Page Break inside Worksheet using Aspose.Cells for Cloud API.

```java

//Your workbook and sheet name

string workbookName = "sampleExcelPageBreaks.xlsx";

string sheetName = "Sheet1";



//Column index to insert vertical page break

int idxCol = 9;



//URL to insert vertical page break

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/verticalpagebreaks?column=" + idxCol;



//Call PUT method with the following parameters

string data = "";

string contentType = "application/json";

using (HttpWebResponse response = \_helper.CallPut(url, data, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **Delete Horizontal Page Break inside Worksheet**
The following sample code illustrates how to get delete Horizontal Page Break inside Worksheet using Aspose.Cells for Cloud API.

```java

//Your workbook and sheet name

string workbookName = "sampleExcelPageBreaks.xlsx";

string sheetName = "Sheet1";



//Your horizontal page break index

int idxHorizontalPageBreak = 0;



//URL to Delete Horizontal Page Break

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/horizontalpagebreaks/" + idxHorizontalPageBreak;



//Call Delete method with the following parameters

string data = "";

string contentType = "application/json";

using (HttpWebResponse response = \_helper.CallDelete(url, data, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **Delete Vertical Page Break inside Worksheet**
The following sample code illustrates how to get delete Vertical Page Break inside Worksheet using Aspose.Cells for Cloud API.

```java

//Your workbook and sheet name

string workbookName = "sampleExcelPageBreaks.xlsx";

string sheetName = "Sheet1";



//Your vertical page break index

int idxVerticalPageBreak = 0;



//URL to Delete Vertical Page Break

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/verticalpagebreaks/" + idxVerticalPageBreak;



//Call Delete method with the following parameters

string data = "";

string contentType = "application/json";

using (HttpWebResponse response = \_helper.CallDelete(url, data, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **AutoFit Single Column of Worksheet**
The following sample code illustrates how to autofit single column of the worksheet. It autofits the **column C**.

```java

//Your workbook and sheet name

string workbookName = "sampleAutoFit.xlsx";

string sheetName = "Sheet1";



//URL to auto fit the column C

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/autofitcolumns?firstColumn=2&lastColumn=2";



//Call POST method with the above URL

using (HttpWebResponse response = \_helper.CallPost(url, string.Empty, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **AutoFit Multiple Columns of Worksheet**
The following sample code illustrates how to autofit multiple columns of the worksheet. It autofits the **columns A, B, C, D, E and F**.

```java

//Your workbook and sheet name

string workbookName = "sampleAutoFit.xlsx";

string sheetName = "Sheet1";



//URL to auto fit the columns A, B, C, D, E and F

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/autofitcolumns?firstColumn=0&lastColumn=5";



//Call POST method with the above URL

using (HttpWebResponse response = \_helper.CallPost(url, string.Empty, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **AutoFit Single Row of Worksheet**
The following sample code illustrates how to autofit single row of the worksheet. It autofits the **2nd row**.

```java

//Your workbook and sheet name

string workbookName = "sampleAutoFitRow.xlsx";

string sheetName = "Sheet1";



//URL to auto fit the 2nd row

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/autofitrow?rowIndex=1&firstColumn=1&lastColumn=10";



//Call POST method with the above URL

using (HttpWebResponse response = \_helper.CallPost(url, string.Empty, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **AutoFit Multiple Rows of Worksheet**
The following sample code illustrates how to autofit multiple rows of the worksheet. It autofits the multiple rows starting from 2nd row to 8th row.

```java

//Your workbook and sheet name

string workbookName = "sampleAutoFitRows.xlsx";

string sheetName = "Sheet1";



//URL to auto fit the multiple rows from 2nd to 8th

string url = "http://api.aspose.com/v1.1/cells/" + workbookName + "/worksheets/" + sheetName + "/autofitrows?onlyAuto=False&startRow=1&endRow=7";



//Call POST method with the above URL

using (HttpWebResponse response = \_helper.CallPost(url, string.Empty, contentType))

{

    Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

}

```
#### **Usage Examples**
Please check the list of help topics added in the Aspose.Cells Wiki docs: 

1. [Get Horizontal Page Breaks inside Worksheet](https://docs.aspose.com/display/cellscloud/Get+Horizontal+Page+Breaks+inside+Worksheet)
1. [Get Vertical Page Breaks inside Worksheet](https://docs.aspose.com/display/cellscloud/Get+Vertical+Page+Breaks+inside+Worksheet)
1. [Insert Horizontal Page Break inside Worksheet](https://docs.aspose.com/display/cellscloud/Insert+Horizontal+Page+Break+inside+Worksheet)
1. [Insert Vertical Page Break inside Worksheet](https://docs.aspose.com/display/cellscloud/Insert+Vertical+Page+Break+inside+Worksheet)
1. [Delete Horizontal Page Break inside Worksheet](https://docs.aspose.com/display/cellscloud/Delete+Horizontal+Page+Break+inside+Worksheet)
1. [Delete Vertical Page Break inside Worksheet](https://docs.aspose.com/display/cellscloud/Delete+Vertical+Page+Break+inside+Worksheet)
1. [AutoFit Single Column of Worksheet](https://docs.aspose.com/display/cellscloud/AutoFit+Single+Column+of+Worksheet)
1. [AutoFit Multiple Columns of Worksheet](https://docs.aspose.com/display/cellscloud/AutoFit+Multiple+Columns+of+Worksheet)
1. [AutoFit Single Row of Worksheet](https://docs.aspose.com/display/cellscloud/AutoFit+Single+Row+of+Worksheet)
1. [AutoFit Multiple Rows of Worksheet](https://docs.aspose.com/display/cellscloud/AutoFit+Multiple+Rows+of+Worksheet)
