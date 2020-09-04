---
title: "Working with Pivot Table using CellsObjectOperate Task"
type: docs
url: /working-with-pivot-table-using-cellsobjectoperate-task/
weight: 120
---

## **Working with Pivot Table using CellsObjectOperate Task**
The following sample code illustrates how to work with Pivot Table using CellsObjectOperate Task object with Aspose.Cells for Cloud.
## **Sample Code**
**C#**

```csharp

public void Run\_PivotTable\_TaskPivot()

{

    string xml = "<?xml version=\"1.0\"?>" +

                "<TaskData xmlns:xsd=\"http://www.w3.org/2001/XMLSchema\" xmlns:xsi=\"http://www.w3.org/2001/XMLSchema-instance\">" +

                @"<Tasks>

                <TaskDescription>

                    <TaskType>ImportData</TaskType>

                    <ImportDataTaskParameter>

                    <Workbook>

                        <FileSourceType>CloudFileSystem</FileSourceType>

                        <FilePath>Book1.xlsx</FilePath>

                    </Workbook>

                    <ImportBatchDataOption>

                        <DestinationWorksheet>Sheet2</DestinationWorksheet>

                        <IsInsert>true</IsInsert>

                        <BatchData>

                        <CellValue>

                            <rowIndex>0</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Sport</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>0</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>String</type>

                            <value>Year</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>0</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Quarter</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>0</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>String</type>

                            <value>Sales</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>0</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>String</type>

                            <value>YearSales</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>1</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Golf</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>2</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Golf</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>3</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Tennis</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>4</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Tennis</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>5</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Tennis</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>6</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Tennis</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>7</rowIndex>

                            <columnIndex>0</columnIndex>

                            <type>String</type>

                            <value>Golf</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>1</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2014</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>2</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2014</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>3</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2014</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>4</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2013</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>5</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2013</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>6</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2013</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>7</rowIndex>

                            <columnIndex>1</columnIndex>

                            <type>int</type>

                            <value>2013</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>1</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr3</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>2</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr4</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>3</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr3</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>4</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr4</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>5</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr3</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>6</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr4</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>7</rowIndex>

                            <columnIndex>2</columnIndex>

                            <type>String</type>

                            <value>Qtr3</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>1</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>1500</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>2</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>2000</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>3</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>600</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>4</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>1500</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>5</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>4070</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>6</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>5000</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>7</rowIndex>

                            <columnIndex>3</columnIndex>

                            <type>int</type>

                            <value>6430</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>1</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>15000</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>2</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>20000</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>3</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>600</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>4</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>1500</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>5</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>4070</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>6</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>5000</value>

                        </CellValue>

                        <CellValue>

                            <rowIndex>7</rowIndex>

                            <columnIndex>4</columnIndex>

                            <type>int</type>

                            <value>6430</value>

                        </CellValue>

                        </BatchData>

                    </ImportBatchDataOption>

                    </ImportDataTaskParameter>

                </TaskDescription>

                <TaskDescription>

                    <TaskType>CellsObjectOperate</TaskType>

                    <CellsObjectOperateTaskParameter>

                    <OperateObject>

                        <OperateObjectType>ListObject</OperateObjectType>

                        <Position>

                        <Workbook>

                            <FileSourceType>InMemoryFiles</FileSourceType>

                            <FilePath>Book1.xlsx</FilePath>

                        </Workbook>

                        <SheetName>Sheet1</SheetName>

                        <ListObjectIndex>0</ListObjectIndex>

                        </Position>

                    </OperateObject>

                    <PivotTableOperateParameter>

                        <OperateType>Add</OperateType>

                        <SourceData>=Sheet2!A1:E8</SourceData>

                        <DestCellName>C1</DestCellName>

                        <TableName>TestPivot</TableName>

                        <UseSameSource>true</UseSameSource>

                        <PivotTableIndex>0</PivotTableIndex>

                        <PivotFieldRows>

                        <int>0</int>

                        <int>1</int>

                        </PivotFieldRows>

                        <PivotFieldColumns>

                        <int>2</int>

                        </PivotFieldColumns>

                        <PivotFieldData>

                        <int>3</int>

                        <int>4</int>

                        </PivotFieldData>

                    </PivotTableOperateParameter>

                    <DestinationWorkbook>

                        <FileSourceType>InMemoryFiles</FileSourceType>

                        <FilePath>Book001.xlsx</FilePath>

                    </DestinationWorkbook>

                    </CellsObjectOperateTaskParameter>

                </TaskDescription>

                <TaskDescription>

                    <TaskType>SaveResult</TaskType>

                    <SaveResultTaskParameter>

                    <ResultSource>InMemoryFiles</ResultSource>

                    <ResultDestination>

                        <DestinationType>OutputStream</DestinationType>

                        <InputFile>Book001.xlsx</InputFile>

                        <OutputFile>Output\ReportS004.xlsx</OutputFile>

                    </ResultDestination>

                    </SaveResultTaskParameter>

                </TaskDescription>

                </Tasks>

            </TaskData>";

    url = "http://api.aspose.com/v3.0/cells/task/runtask";

    using (HttpWebResponse response = \_helper.CallPost(url, xml, "application/xml"))

    {

        Assert.AreEqual(response.StatusCode, HttpStatusCode.OK);

    }

}

```




