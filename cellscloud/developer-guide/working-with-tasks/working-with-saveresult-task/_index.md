---
title: "Working with SaveResult Task"
type: docs
url: /working-with-saveresult-task/
weight: 50
---

## **Introduction**
This example shows how to work with SaveResult Task using Aspose.Cells for Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **Source Excel File and Output Tiff image**
Please upload the [sample excel file](attachments/1540276/1837218.xlsx) in your Cloud File System to run the example. After execution of the code you will get this [output tiff image](attachments/1540276/1837196.tiff).
## **Resource**
The following Aspose.Cells for Cloud REST API resource has been used in the examples: [task](), [saveResult task](), [Convert task]().
## **REST Methods References**
We're referring some common methods in the REST examples to perform general operations. These methods can be found at the following page: [REST API Methods](http://www.aspose.com/docs/display/rest/REST+API+Methods)
## **REST Examples**
![todo:image\_alt\_text](/plugins/servlet/confluence/placeholder/unknown-macro)
#### **C#**
```java

var xml = @"

<TaskData>

  <Tasks>

    <TaskDescription>

      <TaskType>Convert</TaskType>

      <ConvertTaskParameter>

        <Workbook>

          <FileSourceType>CloudFileSystem</FileSourceType>

          <FilePath>Source.xlsx</FilePath>

        </Workbook>

        <DestinationFile>Temp.tiff</DestinationFile>

        <ImageSaveOptions>

          <HorizontalResolution>200</HorizontalResolution>

          <OnePagePerSheet>true</OnePagePerSheet>

          <VerticalResolution>100</VerticalResolution>

        </ImageSaveOptions>

      </ConvertTaskParameter>

    </TaskDescription>

    <TaskDescription>

      <TaskType>SaveResult</TaskType>

      <SaveResultTaskParameter>

        <ResultSource>InMemoryFiles</ResultSource>

        <ResultDestination>

          <DestinationType>OutputStream</DestinationType>

          <InputFile>Temp.tiff</InputFile>

          <OutputFile>Output.tiff</OutputFile>

        </ResultDestination>

      </SaveResultTaskParameter>

    </TaskDescription>

  </Tasks>

</TaskData>

";

ServiceHelper helper = new ServiceHelper(sid, key);

using (HttpWebResponse response = helper.CallPost("http://api.aspose.com/v3.0/cells/task/runtask", xml, "application/xml"))

{

    if (response.StatusCode == HttpStatusCode.OK)

    {

        System.Console.WriteLine("OK");

        Stream st = response.GetResponseStream();

        FileStream fs = new FileStream("Output.tiff", FileMode.OpenOrCreate);

        st.CopyTo(fs);

    }

}


```
#### **VB.NET**
```java

Dim xml = "<TaskData><Tasks><TaskDescription><TaskType>Convert</TaskType><ConvertTaskParameter><Workbook><FileSourceType>CloudFileSystem</FileSourceType><FilePath>Source.xlsx</FilePath></Workbook><DestinationFile>Temp.tiff</DestinationFile><ImageSaveOptions><HorizontalResolution>200</HorizontalResolution><OnePagePerSheet>true</OnePagePerSheet><VerticalResolution>100</VerticalResolution></ImageSaveOptions></ConvertTaskParameter></TaskDescription><TaskDescription><TaskType>SaveResult</TaskType><SaveResultTaskParameter><ResultSource>InMemoryFiles</ResultSource><ResultDestination><DestinationType>OutputStream</DestinationType><InputFile>Temp.tiff</InputFile><OutputFile>Output.tiff</OutputFile></ResultDestination></SaveResultTaskParameter></TaskDescription></Tasks></TaskData>"

Dim helper As New ServiceHelper(sid, key)

Using response As HttpWebResponse = helper.CallPost("http://api.aspose.com/v3.0/cells/task/runtask", xml, "application/xml")

	If response.StatusCode = HttpStatusCode.OK Then

		System.Console.WriteLine("OK")

		Dim st As Stream = response.GetResponseStream()

		Dim fs As New FileStream("Output.tiff", FileMode.OpenOrCreate)

		st.CopyTo(fs)

	End If

End Using



```
