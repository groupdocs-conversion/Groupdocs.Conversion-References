---
title: "एक दस्तावेज़ को दूसरे फ़ॉर्मेट में बदलें"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एकल दस्तावेज़ को एक फ़ॉर्मेट से दूसरे में बदलें, वैकल्पिक रूप से ConvertOptions पर pages / page_number / pages_count एट्रिब्यूट्स का उपयोग करके विशिष्ट पृष्ठ या पृष्ठ रेंज चुनें, GroupDocs.Conversion for Python via .NET के साथ।"
type: docs
url: /hi/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


यह दस्तावेज़ विषय एकल दस्तावेज़ को दूसरे फ़ॉर्मेट में बदलने को कवर करता है, जहाँ केवल एक दस्तावेज़ आउटपुट के रूप में उत्पन्न होता है। निम्नलिखित आरेख एक फ़ाइल को एक फ़ॉर्मेट से दूसरे में बदलने की प्रक्रिया को दर्शाता है:

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e. g. PDF)\"]

%% Edge connections between nodes
A --> B --> C

एक दस्तावेज़ को बदलने और सहेजने के लिए, निम्नलिखित [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) क्लास मेथड्स का उपयोग करें:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

निम्नलिखित [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासों की सूची का उपयोग दस्तावेज़ को एक विशिष्ट एकल आउटपुट फ़ॉर्मेट में बदलने के लिए किया जा सकता है:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

निम्नलिखित उदाहरण दिखाता है कि DOCX फ़ाइल को PDF में कैसे बदलें:

{{< tabs \"example-1\">}}
{{< tab \"convert_document_to_another_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें 
    with Converter("./business-plan.docx") as converter:
        # आउटपुट फ़ॉर्मेट निर्धारित करने के लिए कन्वर्ट विकल्पों का इंस्टैंसिएट करें
        pdf_convert_options = PdfConvertOptions()
        
        # इनपुट दस्तावेज़ को PDF में बदलें
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

डिफ़ॉल्ट रूप से, प्रत्येक [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लास की अपनी डिफ़ॉल्ट लक्ष्य फ़ॉर्मेट होती है। उदाहरण के लिए, [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) की डिफ़ॉल्ट आउटपुट फ़ॉर्मेट [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/) है।

`format` प्रॉपर्टी का उपयोग करके फ़ॉर्मेट परिवार के भीतर अलग आउटपुट फ़ॉर्मेट सेट करें। निम्नलिखित उदाहरण दिखाता है कि `DOCX` फ़ाइल को बदलते समय लक्ष्य फ़ॉर्मेट को `TXT` कैसे निर्दिष्ट करें:

{{< tabs \"example-2\">}}
{{< tab \"specify_output_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें 
    with Converter("./business-plan.docx") as converter:
        # कन्वर्ट विकल्पों को इंस्टैंटिएट करें ताकि आउटपुट फ़ॉर्मेट निर्धारित किया जा सके, डिफ़ॉल्ट रूप से यह DOCX है
        word_convert_options = WordProcessingConvertOptions()
        # फ़ॉर्मेट परिवार के भीतर आउटपुट फ़ॉर्मेट को DOCX से TXT में बदलें
        word_convert_options.format = WordProcessingFileType.TXT
        
        # इनपुट दस्तावेज़ को TXT में कनवर्ट करें
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"business-plan.txt\" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

जाने कि दस्तावेज़ पृष्ठों की संख्या कैसे प्राप्त करें [Getting Document Information]() दस्तावेज़ीकरण विषय में।

विशिष्ट दस्तावेज़ पृष्ठों को बदलने के लिए, आप निम्नलिखित [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासेस का उपयोग कर सकते हैं, जो `pages`, `page_number`, और `pages_count` एट्रिब्यूट प्रदान करती हैं। ये विकल्प आपको व्यक्तिगत पृष्ठों या पृष्ठों की रेंज को बदलने के लिए निर्दिष्ट करने की अनुमति देते हैं।

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).

### Example 1: Convert Specific Document Pages to Another Format

आप निर्दिष्ट कर सकते हैं कि आप कौन से दस्तावेज़ पृष्ठ बदलना चाहते हैं, जैसा कि निम्नलिखित उदाहरण में दिखाया गया है:

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें 
    with Converter("./business-plan.docx") as converter:
        # आउटपुट फ़ॉर्मेट निर्धारित करने के लिए कन्वर्ट विकल्पों का इंस्टैंसिएट करें
        pdf_convert_options = PdfConvertOptions()
        # कौन से दस्तावेज़ पृष्ठ बदलने हैं, निर्दिष्ट करें
        pdf_convert_options.pages = [1, 3, 5]

        # इनपुट दस्तावेज़ के निर्दिष्ट पृष्ठों को PDF में बदलें
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"pages-1-3-5.pdf\" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

एक विकल्प के रूप में, आप लगातार पृष्ठों की संख्या निर्दिष्ट कर सकते हैं जिसे बदलना है, जैसा कि निम्नलिखित उदाहरण में दिखाया गया है:

{{< tabs \"example-4\">}}
{{< tab \"convert_consecutive_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें 
    with Converter("./business-plan.docx") as converter:
        # आउटपुट फ़ॉर्मेट निर्धारित करने के लिए कन्वर्ट विकल्पों का इंस्टैंसिएट करें
        pdf_convert_options = PdfConvertOptions()
        # बदलने के लिए प्रारंभिक पृष्ठ और पृष्ठों की संख्या निर्दिष्ट करें
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # दस्तावेज़ में निर्दिष्ट पृष्ठ रेंज को PDF में बदलें
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"pages-1-through-5.pdf\" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
