---
title: "संभव रूपांतरण प्राप्त करें"
linkTitle: "Get Possible Conversions"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Conversion for Python को .NET के माध्यम से क्वेरी करें ताकि किसी स्रोत द्वारा समर्थित लक्ष्य फ़ॉर्मेट्स का सेट प्राप्त किया जा सके — लाइब्रेरी‑व्यापी, एक्सटेंशन द्वारा, या वर्तमान में लोड किए गए दस्तावेज़ के लिए — get_all_possible_conversions, get_possible_conversions_by_extension, और get_possible_conversions के माध्यम से।"
type: docs
url: /hi/python-net/guides/get-possible-conversions/
is_root: false
weight: 50
---


GroupDocs.Conversion संभावित रूपांतरण प्राप्त करने के लिए कई मेथड प्रदान करता है:

- **`Converter.get_all_possible_conversions()`**: Retrieves all available primary and secondary conversions for every supported file type.
- **`Converter.get_possible_conversions_by_extension(extension: str)`**: Retrieves possible conversions for a specific file extension, e.g., `"docx"`.
- **`converter.get_possible_conversions()`**: Retrieves possible conversions for the currently loaded file.

### Types of Conversions
* **Primary Conversion**: A direct conversion from one format to another, providing higher quality and better performance.
* **Secondary Conversion**: An indirect conversion that requires the source file to be first converted to an intermediate format before reaching the final format.

## Example 1: Get All Possible Conversions

निम्न उदाहरण दिखाता है कि प्रत्येक समर्थित फ़ाइल प्रकार के लिए सभी प्राथमिक और द्वितीयक रूपांतरण कैसे प्राप्त और प्रदर्शित किए जाएँ।

{{< tabs \"example-1\">}}
{{< tab "get_all_possible_conversions.py" >}}
```python
from groupdocs.conversion import Converter

# GroupDocs.Conversion 150+ स्रोत फ़ॉर्मेट्स का समर्थन करता है; पहले N को प्रिंट करें
# कंसोल आउटपुट को पठनीय रखने के लिए। सीमा बढ़ाएँ या हटाएँ ताकि देखें
# प्रत्येक स्रोत फ़ॉर्मेट।
SAMPLE_LIMIT = 3

def get_all_possible_conversions():
    # प्रत्येक समर्थित स्रोत फ़ॉर्मेट के लिए सभी संभावित रूपांतरण प्राप्त करें
    all_possible_conversions = list(Converter.get_all_possible_conversions())

    print(f"Total supported source formats: {len(all_possible_conversions)}")
    print(f"Showing the first {SAMPLE_LIMIT} as a sample.")
    print()

    for possible_conversion in all_possible_conversions[:SAMPLE_LIMIT]:
        # इस स्रोत के लिए प्राथमिक / द्वितीयक लक्ष्य एक्सटेंशन एकत्र करें
        primary_conversions = [c.format.extension for c in possible_conversion.all if c.is_primary]
        secondary_conversions = [c.format.extension for c in possible_conversion.all if not c.is_primary]

        # स्रोत फ़ॉर्मेट और उसके लक्ष्य एक्सटेंशन को प्रिंट करें
        print(f"Source format: {possible_conversion.source.description}")
        print(f"  Primary target formats  ({len(primary_conversions)}): {primary_conversions}")
        print(f"  Secondary target formats ({len(secondary_conversions)}): {secondary_conversions}")
        print()

if __name__ == "__main__":
    get_all_possible_conversions()
```
{{< /tab >}}
{{< tab "get-all-possible-conversions.txt" >}}
```text
Total supported source formats: 208
Showing the first 3 as a sample.

Source format: MP3 Audio File (mp3)
  Primary target formats  (9): ['mp3', 'aac', 'aiff', 'flac', 'm4a', 'wma', 'ac3', 'ogg', 'wav']
  Secondary target formats (0): []

Source format: Advanced Audio Coding File (aac)
  Primary target formats  (9): ['mp3', 'aac', 'aiff', 'flac', 'm4a', 'wma', 'ac3', 'ogg', 'wav']
  Secondary target formats (0): []
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions/get-all-possible-conversions.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Get Possible Conversions by File Extension

निम्न उदाहरण दर्शाता है कि कैसे "docx" एक्सटेंशन के लिए संभावित रूपांतरणों को प्राप्त किया जाए और प्रदर्शित किया जाए, जो माइक्रोसॉफ्ट वर्ड ओपन XML दस्तावेज़ के अनुरूप है।

{{< tabs \"example-2\">}}
{{< tab "get_all_possible_conversions_by_file_extension.py" >}}
```python
from groupdocs.conversion import Converter

def get_all_possible_conversions_by_file_extension():
    # एक विशिष्ट एक्सटेंशन के लिए सभी संभावित रूपांतरण प्राप्त करें
    possible_conversion = Converter.get_possible_conversions_by_extension("docx")

    # मुख्य रूपांतरण फ़िल्टर करें (साफ़ स्ट्रिंग के लिए .extension का उपयोग करें)
    primary_conversions = [conversion.format.extension for conversion in possible_conversion.all if conversion.is_primary]
    # द्वितीयक रूपांतरण फ़िल्टर करें
    secondary_conversions = [conversion.format.extension for conversion in possible_conversion.all if not conversion.is_primary]

    # स्रोत फ़ॉर्मेट और उसके रूपांतरण प्रिंट करें
    print(f" **Source format**: {possible_conversion.source.description}")
    print(f"  - **Primary conversions**: {primary_conversions}")
    print(f"  - **Secondary conversions**: {secondary_conversions}")
    print()

if __name__ == "__main__":
    get_all_possible_conversions_by_file_extension()
```
{{< /tab >}}
{{< tab "get-all-possible-conversions-by-file-extension.txt" >}}
```text
**Source format**: Microsoft Word Open XML Document (docx)
  - **Primary conversions**: ['epub', 'mobi', 'azw3', 'tiff', 'tif', 'jpg', 'jpeg', 'png', 'gif', 'bmp', 'ico', 'psd', 'wmf', 'emf', 'dcm', 'dicom', 'webp', 'jp2', 'j2k', 'emz', 'wmz', 'tga', 'psb', 'jfif', 'eps', 'xps', 'tex', 'ps', 'pcl', 'svg', 'svgz', 'pdf', 'ppt', 'pps', 'pptx', 'ppsx', 'odp', 'otp', 'potx', 'pot', 'potm', 'pptm', 'ppsm', 'fodp', 'htm', 'html', 'mhtml', 'mht', 'doc', 'docm', 'docx', 'dot', 'dotm', 'dotx', 'rtf', 'od
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions_by_file_extension/get-all-possible-conversions-by-file-extension.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Possible Conversions for Current File

निम्न उदाहरण दर्शाता है कि कैसे फ़ाइल को [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) क्लास कंस्ट्रक्टर में पास करके संभावित रूपांतरणों को प्राप्त किया जाए और प्रदर्शित किया जाए।

{{< tabs \"example-3\">}}
{{< tab "get_all_possible_conversions_for_current_file.py" >}}
```python
from groupdocs.conversion import Converter

def get_all_possible_conversions_for_current_file():
    with Converter("./cost-analysis.xlsx") as converter:
        # लोड किए गए दस्तावेज़ के लिए संभावित रूपांतरण प्राप्त करें
        possible_conversion = converter.get_possible_conversions()

        # मुख्य रूपांतरण फ़िल्टर करें (साफ़ स्ट्रिंग के लिए .extension का उपयोग करें)
        primary_conversions = [conversion.format.extension for conversion in possible_conversion.all if conversion.is_primary]
        # द्वितीयक रूपांतरण फ़िल्टर करें
        secondary_conversions = [conversion.format.extension for conversion in possible_conversion.all if not conversion.is_primary]

        # स्रोत फ़ॉर्मेट और उसके रूपांतरण प्रिंट करें
        print(f" **Source format**: {possible_conversion.source.description}")
        print(f"  - **Primary conversions**: {primary_conversions}")
        print(f"  - **Secondary conversions**: {secondary_conversions}")
        print()

if __name__ == "__main__":
    get_all_possible_conversions_for_current_file()
```
{{< /tab >}}
{{< tab "get-all-possible-conversions-current-file.txt" >}}
```text
**Source format**: Microsoft Excel Open XML Spreadsheet (xlsx)
  - **Primary conversions**: ['epub', 'mobi', 'azw3', 'eps', 'xps', 'tex', 'ps', 'pcl', 'pdf', 'xls', 'xlsx', 'xlsm', 'xlsb', 'ods', 'xltx', 'xlt', 'xltm', 'tsv', 'xlam', 'csv', 'fods', 'dif', 'sxc', 'fopcs', 'htm', 'html', 'mhtml', 'mht', 'json', 'xml']
  - **Secondary conversions**: ['tiff', 'tif', 'jpg', 'jpeg', 'png', 'gif', 'bmp', 'ico', 'psd', 'wmf', 'emf', 'dcm', 'dicom', 'webp', 'jp2', 'j2k', 'emz', 'wmz', 'tga', 'psb', 'jfif
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions_for_current_file/get-all-possible-conversions-current-file.txt)
{{< /tab >}}
{{< /tabs >}}
