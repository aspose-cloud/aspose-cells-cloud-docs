---
title: "Working with ImportData Task"
type: docs
url: /working-with-importdata-task/
weight: 40
---

## **Introduction**
This example shows how to use Task API to import data into a worksheet and save the workbook with new name on the Cloud. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **Source and Output Excel Files**
Please upload this [sample excel file](attachments/1540443/1839151.xlsx) to the cloud. The Task API will save [this file](attachments/1540443/1839152.xlsx) as an output excel file[ ](attachments/1540443/1839152.xlsx) on the Cloud.
## **Resource**
The following Aspose.Cells for Cloud REST API resource has been used in the examples: [task](), [ImportData Task]() and [saveResult task]().
## **REST Methods References**
We're referring some common methods in the REST examples to perform general operations. These methods can be found at the following page: [REST API Methods](http://www.aspose.com/docs/display/rest/REST+API+Methods)
## **SDK Source**
The Aspose for Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **cURL Example**
{{< tabs tabTotal="2" tabID="5" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/task/runtask?appSid=B01A15E5-1B83-4B9A-8EB3-0F2BFA6AC766&signature=8IHfiBxpe9TI7ks%2BLflwMGPzSis" \
-X POST \
-F 'json={

  "Tasks": [

    {

      "TaskType": 1,

      "TaskParameter": {

        "Workbook": {

          "FileSourceType": 1,

          "FilePath": "Book1.xlsx"

        },

        "ImportOption": {

          "FirstRow": 1,

          "FirstColumn": 1,

          "IsVertical": false,

          "Data": [

            10.0,

            1.222,

            4.003

          ],

          "DestinationWorksheet": "Sheet1",

          "IsInsert": true,

          "ImportDataType": null,

          "Source": null

        },

        "DestinationWorkbook": null

      }

    },

    {

      "TaskType": 4,

      "TaskParameter": {

        "ResultSource": 1,

        "ResultDestination": {

          "DestinationType": 1,

          "InputFile": "Book1.xlsx",

          "OutputFile": "Book2.xlsx"

        }

      }

    }

  ]

};type=application/json' \
-H "Content-Type: multipart/form-data" \
-H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"SavedFiles":[{"Href":"Book2.xlsx","Rel":"saved","Title":null,"Type":null}]}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Examples**
{{< tabs tabTotal="5" tabID="8" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Node.js" tabName5="Perl" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNet-CSharp-Tasks-ImportTaskData-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostTaskDataMultipart-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Workbook-post_run_task-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Tasks-ImportTaskData-1.js" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-ImportData-postImportDataMultipartContent-1.pl" >}}

{{< /tab >}}

{{< /tabs >}}

