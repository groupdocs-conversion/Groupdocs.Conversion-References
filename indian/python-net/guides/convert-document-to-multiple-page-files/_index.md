---
title: "दस्तावेज़ को कई पृष्ठ फ़ाइलों में परिवर्तित करें"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /hi/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: दस्तावेज़ को कई पृष्ठ फ़ाइलों में परिवर्तित करें
linkTitle: कई फ़ाइलों में परिवर्तित करें
weight: 3
description: "एक बहु‑पृष्ठ दस्तावेज़ के प्रत्येक पृष्ठ को उसके स्वयं के आउटपुट फ़ाइल में रेंडर करें — page_number को pages_count=1 के साथ लूप करें और Converter.convert() का उपयोग करके प्रत्येक पृष्ठ के लिए एक PNG, PDF, या इमेज उत्पन्न करें, GroupDocs.Conversion for Python via .NET के साथ।"
keywords: कई फ़ाइलों में परिवर्तित करें, प्रति‑पृष्ठ आउटपुट, page_number, pages_count, पृष्ठ लूप, प्रस्तुति पृष्ठों को परिवर्तित करें, PDF पृष्ठों को PNG में परिवर्तित करें, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

यह दस्तावेज़ विषय एकल बहु‑पृष्ठ दस्तावेज़ को व्यक्तिगत पृष्ठ फ़ाइलों में परिवर्तित करने को कवर करता है। निम्नलिखित आरेख बहु‑पृष्ठ फ़ाइल को अलग‑अलग पृष्ठों में बदलने की प्रक्रिया को दर्शाता है:

flowchart LR
%% Nodes
A["इनपुट दस्तावेज़"]
B[\"Conversion\"]
C["परिवर्तित पृष्ठ 1"]
D["परिवर्तित पृष्ठ 2"]
E["परिवर्तित पृष्ठ N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

एक दस्तावेज़ को प्रति‑पृष्ठ फ़ाइलों में परिवर्तित करने के लिए, `Converter.convert(file_path, convert_options)` मेथड को `page_number` और `pages_count` एट्रिब्यूट्स के साथ उपयोग करें, जो समर्थित [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासेज़ पर उपलब्ध हैं:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

प्रति पृष्ठ एक आउटपुट फ़ाइल उत्पन्न करने के लिए, `1` से `converter.get_document_info().pages_count` तक लूप करें, प्रत्येक इटरशन में `page_number` को अपडेट करें और अलग आउटपुट पाथ पर लिखें। `pages_count = 1` सेट करने से प्रत्येक कॉल एक ही पृष्ठ जारी करता है।

## Supported ConvertOptions Classes

निम्नलिखित [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासेज़ इस विषय में उपयोग किए गए `page_number` और `pages_count` एट्रिब्यूट्स को उजागर करती हैं:

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

## Example 1: Convert All Pages of a Document and Save Output to a Folder

निम्नलिखित उदाहरण दर्शाता है कि PPTX प्रस्तुति की प्रत्येक स्लाइड को PNG इमेज में कैसे परिवर्तित किया जाए और आउटपुट इमेज को निर्दिष्ट फ़ोल्डर में कैसे सहेजा जाए।
 
आउटपुट फ़ाइलों के लिए फ़ाइल नाम टेम्प्लेट `converted-page-{page number}.{output file extension}` है। इस उदाहरण में, पहली स्लाइड `converted-page-1.png` के रूप में सहेजी जाएगी।

{{< tabs \"example-1\">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें
    with Converter("./basic-presentation.pptx") as converter:
        # स्रोत दस्तावेज़ में कुल पृष्ठों की संख्या निर्धारित करें
        pages_count = converter.get_document_info().pages_count

        # एक बार कन्वर्ट विकल्प को इंस्टैंशिएट करें और लूप के भीतर उन्हें पुन: उपयोग करें
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # प्रत्येक पृष्ठ को अलग PNG फ़ाइल में परिवर्तित करें
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) क्लिक करें।

{{< /tab >}}
{{< tab "convert-all-document-pages-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

जाने कि दस्तावेज़ पृष्ठों की संख्या कैसे प्राप्त करें [Getting Document Information]() दस्तावेज़ीकरण विषय में।

निम्नलिखित उदाहरण दिखाता है कि PPTX प्रस्तुति में एक विशिष्ट स्लाइड को कैसे परिवर्तित किया जाए और उसे अलग फ़ाइल के रूप में सहेजा जाए।

{{< tabs \"example-2\">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें
    with Converter("./basic-presentation.pptx") as converter:
        # कन्वर्ट विकल्पों को इंस्टैंशिएट करें
        png_convert_options = ImageConvertOptions()
        # आउटपुट फ़ॉर्मेट को PNG के रूप में निर्धारित करें
        png_convert_options.format = ImageFileType.PNG

        # कनवर्ट करने के लिए एकल पृष्ठ निर्दिष्ट करें
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # कनवर्ट किए गए पृष्ठ को फ़ाइल में सहेजें
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) क्लिक करें।

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

जाने कि दस्तावेज़ पृष्ठों की संख्या कैसे प्राप्त करें [Getting Document Information]() दस्तावेज़ीकरण विषय में।

यदि आपको कनवर्ट किया गया पृष्ठ इन‑मेमोरी बफ़र के रूप में चाहिए (उदाहरण के लिए, इसे बाद में फ़ाइल सिस्टम को छुए बिना किसी अन्य API को फ़ॉरवर्ड करने के लिए), पहले पृष्ठ को फ़ाइल में कनवर्ट करें और फिर उसे `BytesIO` ऑब्जेक्ट में पढ़ें:

{{< tabs \"example-3\">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें
    with Converter("./basic-presentation.pptx") as converter:
        # कन्वर्ट विकल्पों को इंस्टैंशिएट करें
        png_convert_options = ImageConvertOptions()
        # आउटपुट फ़ॉर्मेट को PNG के रूप में निर्धारित करें
        png_convert_options.format = ImageFileType.PNG

        # कनवर्ट करने के लिए एकल पृष्ठ निर्दिष्ट करें
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # पृष्ठ को डिस्क पर फ़ाइल में कनवर्ट करें और सहेजें
        converter.convert(output_file, png_convert_options)

    # कनवर्ट किए गए पृष्ठ को डाउनस्ट्रीम उपयोग के लिए इन‑मेमोरी स्ट्रीम में लोड करें
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream अब PNG बाइट्स रखता है और इसे किसी भी उपभोक्ता को पास किया जा सकता है
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) क्लिक करें।

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
