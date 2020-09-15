---
title: "Remove a Particular Document Property"
type: docs
url: /remove-a-particular-document-property/
weight: 50
---

## **Introduction**
This example shows how to remove a particular property from a Excel Workbook. Aspose.Cells Cloud API.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/documentproperties/{propertyName}|DELETE|Remove a particular property|[DeleteDocumentProperty](https://apireference.aspose.cloud/cells/#/Properties/DeleteDocumentProperty)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/cells/test.xlsx/documentproperties/author" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1Njk2OTg3NzcsImV4cCI6MTU2OTc4NTE3NywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.cTT1ew15ns0DFsstBkOidtlQcQsQMrlbOoA0kH1rA7R6kUbgwrHbC\_Us1AN5xsHe8Gb8R\_y8sSbDenm3xJkkSWSNXzOB7zr7HhK79sp-vUyfXkx8MCXFDlXdysNGT6ifZCag45PUgG-PQAnB2bpgrTQu8vIHyue5Iz4Wl9o\_FfTGlPsqNEQRXFY39mpsGD6jp0b2B-J3NI4fNwLILRs3GRX273\_5BCmAEf4o8Q72a1IlRzrGZK20gZ6V4\_CLUdMIG3CeE6Uojx97iLA7BpTFq4UdbMCLMTeexV1mWPdQ\_dMZ5zRsdIJVfvT169yx81P3gMeMSOBUv4\_Su9BO6KVqEw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "DocumentProperties": {

    "DocumentPropertyList": [

      {

        "Name": "Title",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Title",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Subject",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Subject",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Author",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Author",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Keywords",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Keywords",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Comments",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Comments",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "LastSavedBy",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/LastSavedBy",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Category",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Category",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "NameOfApplication",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/NameOfApplication",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Version",

        "Value": "14.0300",

        "BuiltIn": "True",

        "link": {

          "Href": "/Version",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Security",

        "Value": "0",

        "BuiltIn": "True",

        "link": {

          "Href": "/Security",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "ScaleCrop",

        "Value": "False",

        "BuiltIn": "True",

        "link": {

          "Href": "/ScaleCrop",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Template",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Template",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Manager",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Manager",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "Company",

        "Value": "",

        "BuiltIn": "True",

        "link": {

          "Href": "/Company",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      },

      {

        "Name": "LinksUpToDate",

        "Value": "False",

        "BuiltIn": "True",

        "link": {

          "Href": "/LinksUpToDate",

          "Rel": "self",

          "Title": null,

          "Type": null

        }

      }

    ],

    "link": {

      "Href": "/test.xlsx/documentproperties",

      "Rel": "self",

      "Title": null,

      "Type": null

    }

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
{{< tabs tabTotal="11" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Python" tabName6="Node.js" tabName7="Android" tabName8="Objective C" tabName9="Perl" tabName10="Go" tabName11="Swift" >}}

{{< tab tabNum="1" >}}

{{< gist "" "0c40af270fa7ae0ad4ec3936676653b8" "Examples-DotNET-CSharp-Document-Properties-RemoveParticularProperty-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cells" "e6fd01c4bbf280df7d4b09796edd8d66" "Examples-Java-SDK-src-main-java-com-aspose-cells-cloud-examples-properties-RemoveParticularProperty-remove-particular-property.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cells" "53fb9eb3d3d0d6e836078d4677a51ab5" "Examples-Ruby-Document-delete\_document\_property-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cells" "7d86d3fa01334f7cee49097d5446e46b" "RemoveParticularDocumentProperty.py" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "" "610ddf5b691b8385a63a29ae6ec89b06" "Examples-Node.js-SDK-Document-Properties-RemoveParticularProperty-1.js" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "5e354c1674e561aeb369d1d0f697ddbc" "Examples-Android-app-src-main-java-com-aspose-cells-cloud-examples-properties-RemoveParticularProperty-remove-particular-property.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "" "a85d029d5a3d47e9d542dd267ae67cdc" "Examples-Perl-Document-Properties-RemoveParticularProperty-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "998e9933fd0e00942039175ebc85a76f" >}}

{{< /tab >}}

{{< tab tabNum="11" >}}

{{< gist "aspose-cloud" "1d4dd557dfa1834527376159043d428b" >}}

{{< /tab >}}

{{< /tabs >}}
