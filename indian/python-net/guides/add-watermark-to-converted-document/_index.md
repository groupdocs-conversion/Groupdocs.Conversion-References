---
title: "परिवर्तित दस्तावेज़ में वॉटरमार्क जोड़ें"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Conversion for Python via .NET के साथ परिवर्तित दस्तावेज़ के प्रत्येक पृष्ठ पर टेक्स्ट वॉटरमार्क स्टैम्प करें — रंग, आकार, स्थिति, घुमाव, पारदर्शिता, और अग्रभूमि या पृष्ठभूमि स्थान को WatermarkTextOptions के माध्यम से नियंत्रित करें।"
type: docs
url: /hi/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


यह विषय GroupDocs.Conversion for Python via .NET का उपयोग करके परिवर्तन प्रक्रिया के दौरान वॉटरमार्क कैसे जोड़ें, यह समझाता है। वॉटरमार्क को दस्तावेज़ पर तब लागू किया जा सकता है जब वह किसी अन्य प्रारूप में परिवर्तित हो रहा हो, जिससे सामग्री की सुरक्षा और पहचान सुनिश्चित होती है।

वॉटरमार्किंग सक्षम करने के लिए, आप उपयुक्त [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासों में `watermark` एट्रिब्यूट का उपयोग कर सकते हैं। नीचे समर्थित [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासें दी गई हैं जो परिवर्तन के दौरान वॉटरमार्क को कॉन्फ़िगर करने की अनुमति देती हैं:

उन्नत वॉटरमार्किंग क्षमताओं की तलाश है? जबकि GroupDocs.Conversion बुनियादी वॉटरमार्किंग प्रदान करता है, आप विस्तारित सुविधाओं के साथ एक व्यापक समाधान के लिए [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) का अन्वेषण कर सकते हैं।

## Supported ConvertOptions Classes

निम्नलिखित [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लासें जो `watermark` एट्रिब्यूट प्रदान करती हैं।

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).

## WatermarkTextOptions Class Attributes

यह [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) क्लास वॉटरमार्क की उपस्थिति को कॉन्फ़िगर करने के लिए उपयोग की जाती है। वॉटरमार्क जोड़ने के लिए निम्न विकल्प कॉन्फ़िगर किए जा सकते हैं:

- **text**: The text to be used for the watermark.
- **font**: The font name used for the watermark text.
- **color**: The color of the watermark text.
- **width**: The width of the watermark.
- **height**: The height of the watermark.
- **top**: The top position of the watermark.
- **left**: The left position of the watermark.
- **rotation_angle**: The rotation angle of the watermark.
- **transparency**: The transparency level of the watermark.
- **background**: Specifies whether the watermark is stamped as a background. If set to `True`, the watermark is placed at the bottom. By default, it is `False`, and the watermark is placed on top of the content.

## Example: Add a Watermark to Converted Document

निम्न उदाहरण दिखाता है कि DOCX दस्तावेज़ को PDF में कैसे परिवर्तित किया जाए और वॉटरमार्क कैसे जोड़ा जाए:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # इनपुट दस्तावेज़ के साथ Converter को इंस्टैंशिएट करें 
    with Converter("./professional-services.docx") as converter:
        # वॉटरमार्क विकल्प सेट करें
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # कन्वर्ज़न विकल्प सेट करें
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # कन्वर्ज़न निष्पादित करें
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
