---
title: "Working with SmartMarker Task"
type: docs
url: /working-with-smartmarker-task/
weight: 60
---

## **Introduction**
This example shows how to work with SmartMarker Task using Aspose.Cells for Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **Designer Spreadsheet and XML DataSet**
Please upload the [Designer Spreadsheet](attachments/1540274/1837214.xlsx) and [XML DataSet](attachments/1540274/1837210.xml) in your Cloud File System to run the example. You can also see [smart marker]() resource which is related to this topic. This is the [output excel file](attachments/1540274/1837211.xlsx) generated after the execution of the code.
## **Resource**
The following Aspose.Cells for Cloud REST API resource has been used in the examples: [task](), [SmartMarker task](), [saveResult task]().
## **REST Methods References**
We're referring some common methods in the REST examples to perform general operations. These methods can be found at the following page: [REST API Methods](http://www.aspose.com/docs/display/rest/REST+API+Methods)
## **REST Examples**
![todo:image_alt_text](/plugins/servlet/confluence/placeholder/unknown-macro)
#### **C#**
```java

var xml = @"<TaskData>

    <Tasks>

    <TaskDescription>

        <TaskType>SmartMarker</TaskType>

        <SmartMarkerTaskParameter>

        <SourceWorkbook>

            <FileSourceType>CloudFileSystem</FileSourceType>

            <FilePath>Designer.xlsx</FilePath>

        </SourceWorkbook>

        <DestinationWorkbook>

            <FileSourceType>InMemoryFiles</FileSourceType>

            <FilePath>Temp.xlsx</FilePath>

        </DestinationWorkbook>

        <xmlFile>

            <FileSourceType>CloudFileSystem</FileSourceType>

            <FilePath>DataSet.xml</FilePath>

        </xmlFile>

        </SmartMarkerTaskParameter>

    </TaskDescription>

    <TaskDescription>

        <TaskType>SaveResult</TaskType>

        <SaveResultTaskParameter>

        <ResultSource>InMemoryFiles</ResultSource>

        <ResultDestination>

            <DestinationType>OutputStream</DestinationType>

            <InputFile>Temp.xlsx</InputFile>

            <OutputFile>Output.xlsx</OutputFile>

        </ResultDestination>

        </SaveResultTaskParameter>

    </TaskDescription>

    </Tasks>

</TaskData>";

ServiceHelper helper = new ServiceHelper(sid, key);

using (HttpWebResponse response = helper.CallPost("http://api.aspose.com/v3.0/cells/task/runtask", xml, "application/xml"))

{

    if (response.StatusCode == HttpStatusCode.OK)

    {

        System.Console.WriteLine("OK");

        Stream st = response.GetResponseStream();

        FileStream fs = new FileStream("Output.xlsx", FileMode.OpenOrCreate);

        st.CopyTo(fs);

    }

}

```
#### **VB.NET**
```java

Dim xml = "<TaskData><Tasks><TaskDescription><TaskType>SmartMarker</TaskType><SmartMarkerTaskParameter><SourceWorkbook><FileSourceType>CloudFileSystem</FileSourceType><FilePath>Designer.xlsx</FilePath></SourceWorkbook><DestinationWorkbook><FileSourceType>InMemoryFiles</FileSourceType><FilePath>Temp.xlsx</FilePath></DestinationWorkbook><xmlFile><FileSourceType>CloudFileSystem</FileSourceType><FilePath>DataSet.xml</FilePath></xmlFile></SmartMarkerTaskParameter></TaskDescription><TaskDescription><TaskType>SaveResult</TaskType><SaveResultTaskParameter><ResultSource>InMemoryFiles</ResultSource><ResultDestination><DestinationType>OutputStream</DestinationType><InputFile>Temp.xlsx</InputFile><OutputFile>Output.xlsx</OutputFile></ResultDestination></SaveResultTaskParameter></TaskDescription></Tasks></TaskData>"

Dim helper As New ServiceHelper(sid, key)

Using response As HttpWebResponse = helper.CallPost("http://api.aspose.com/v3.0/cells/task/runtask", xml, "application/xml")

	If response.StatusCode = HttpStatusCode.OK Then

		System.Console.WriteLine("OK")

		Dim st As Stream = response.GetResponseStream()

		Dim fs As New FileStream("Output.xlsx", FileMode.OpenOrCreate)

		st.CopyTo(fs)

	End If

End Using



```
