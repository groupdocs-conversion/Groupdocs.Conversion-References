---
title: "दस्तावेज़ कंटेनरों के भीतर फ़ाइलों को बदलें"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "ZIP, RAR, 7Z, OST, PST और अन्य कंटेनर फ़ॉर्मेट खोलें, उनकी सामग्री को बदलें, और एक ही Converter.convert() कॉल के साथ GroupDocs.Conversion for Python via .NET में एक समेकित आउटपुट दस्तावेज़ लिखें।"
type: docs
url: /hi/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


यह विषय बताता है कि कैसे दस्तावेज़ कंटेनरों के भीतर एम्बेडेड फ़ाइलों को, जैसे संकुचित या पैकेज्ड फ़ाइलें, व्यक्तिगत आउटपुट फ़ाइलों में बदला जाए। निम्नलिखित आरेख दस्तावेज़ कंटेनर के भीतर फ़ाइलों को निकालने और बदलने की प्रक्रिया को दर्शाता है:

flowchart LR
%% Nodes
A[\"Document Container\"]
B[\"Extraction\"]
C[\"Conversion\"]
D[\"Converted File 1\"]
E[\"Converted File 2\"]
F[\"Converted File N\"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

निकालने और रूपांतरण प्रक्रियाएँ एक ही कॉल में `convert(file_path, convert_options)` मेथड के माध्यम से [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) क्लास की की जाती हैं। GroupDocs.Conversion कंटेनर को खोलता है, उसमें मौजूद फ़ाइलों को रूपांतरित करता है, और एक संयुक्त आउटपुट दस्तावेज़ लिखता है।

## Document Container File Types

निम्नलिखित फ़ाइल प्रकारों को दस्तावेज़ कंटेनर माना जाता है:

### Email and Outlook

- **EML** - Email Message File.
- **EMLX** - Apple Mail Email File.
- **MSG** - Microsoft Outlook Message File.
- **OST** - Outlook Offline Data File.
- **PST** - Outlook Personal Information Store File.

### PDF

- **PDF** - PDF files that contain embedded resources.

### Word Processing

- **DOC** - The older Microsoft Word binary format.
- **DOCX** - The modern Word format.
- **DOT and DOTX** - Word template files.
- **RTF** - Rich Text Format.

### Compression

- **7Z** - 7-Zip Compressed File.
- **BZ2** - Bzip2 Compressed File.
- **CAB** - Windows Cabinet File.
- **CPIO** - CPIO Compressed File.
- **GZ** - Gnu Zipped Archive.
- **GZIP** - Gzip Compressed File.
- **LZ** - Lzip Compressed File.
- **LZMA** - LZMA Compressed File.
- **RAR** - RAR Compressed Archive.
- **TAR** - Consolidated Unix File Archive.
- **XZ** - Xz Compressed File.
- **Z** - Unix Compressed File.
- **ZIP** - ZIP Compressed File.

## Example: Convert Files Within Document Container

निम्न उदाहरण दिखाता है कि ZIP आर्काइव की सामग्री को एक एकल संयुक्त PDF में कैसे रूपांतरित किया जाए:

{{< tabs \"example-1\">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # इनपुट दस्तावेज़ कंटेनर के साथ Converter को इंस्टैंशिएट करें
    with Converter("./compressed.zip") as converter:
        # कन्वर्ट विकल्पों को इंस्टैंशिएट करें
        pdf_convert_options = PdfConvertOptions()

        # आर्काइव को निकालें, उसमें मौजूद फ़ाइलों को रूपांतरित करें, और एक संयुक्त PDF सहेजें
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) क्लिक करें।

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
