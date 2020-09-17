---
title: "Support Request File in Task API"
type: docs
url: /support-request-file-in-task-api/
weight: 10
---

## **Introduction**
This example shows how to request file using a http multipart request in workbook using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "http://api.aspose.cloud/v3.0/cells/myWorkbook.xlsx/SaveAs?newfilename=updatedWorkbook.xlsx&appSID=XXXX&signature=XXXX" \
     -X POST \
     -d '{"ClearData":true}' \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "SaveResult": {

    "SourceDocument": {

      "Href": "myWorkbook.xlsx",

      "Rel": null,

      "Title": null,

      "Type": null

    },

    "DestDocument": {

      "Href": "updatedWorkbook.xlsx",

      "Rel": null,

      "Title": null,

      "Type": null

    },

    "AdditionalItems": [



    ]

  },

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="1" tabID="4" tabName1="PHP" >}}

{{< tab tabNum="1" >}}

{{< gist "" "ac7f938785f2dae1fcb906067f5e06cb" "Examples-PHP-Workbook-PostTaskDataMultipart-.php" >}}

{{< /tab >}}

{{< /tabs >}}
