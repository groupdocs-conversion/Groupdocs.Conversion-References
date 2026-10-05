---
title: "स्थानीय डिस्क से फ़ाइल लोड करें"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Conversion for Python via .NET के साथ स्थानीय फ़ाइल सिस्टम में संग्रहीत दस्तावेज़ को परिवर्तित करने के लिए एक पूर्ण या सापेक्ष फ़ाइल पथ के साथ Converter क्लास को इंस्टैंशिएट करें।"
type: docs
url: /hi/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


अपने स्थानीय डिस्क से स्रोत फ़ाइल लोड करने के लिए, आप GroupDocs.Conversion में [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) क्लास कन्स्ट्रक्टर का उपयोग कर सकते हैं। API कई ओवरलोड प्रदान करता है, जो विभिन्न सेटिंग्स और विकल्पों के लिए लचीलापन देता है:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

प्रत्येक कन्स्ट्रक्टर को `filePath` पैरामीटर की आवश्यकता होती है, जो स्रोत फ़ाइल का पथ निर्धारित करता है। आप इसे पूर्ण या सापेक्ष पथ के रूप में निर्दिष्ट कर सकते हैं। ध्यान दें कि यदि निर्दिष्ट फ़ाइल पथ मौजूद नहीं है, तो एक अपवाद उठाया जाएगा।

GroupDocs.Conversion फ़ाइल तक केवल तब पहुँच करेगा जब कोई कार्रवाई (जैसे, कन्वर्ज़न) [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) क्लास इंस्टेंस का उपयोग करके की जाती है।

निम्न Python उदाहरण स्थानीय डिस्क से फ़ाइल लोड करने और उसे PDF में परिवर्तित करने को दर्शाता है:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # स्रोत फ़ाइल स्थान निर्दिष्ट करें
    converter = Converter("./business-plan.docx")
    
    # आउटपुट फ़ाइल स्थान और कन्वर्ज़न विकल्प निर्दिष्ट करें
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # कन्वर्ट करें और आउटपुट पथ पर सहेजें
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion फ़ाइल प्रकार को उसके एक्सटेंशन द्वारा निर्धारित करता है। यदि फ़ाइल एक्सटेंशन सेट नहीं है, तो GroupDocs.Conversion स्वचालित रूप से फ़ाइल प्रकार का पता लगाने का प्रयास करेगा। फ़ाइल प्रकार और आकार के आधार पर, स्वचालित फ़ाइल प्रकार पहचान अतिरिक्त संसाधनों, जैसे मेमोरी और CPU समय, का उपभोग करती है। इसलिए, हम अनुशंसा करते हैं कि फ़ाइल का सही एक्सटेंशन सुनिश्चित किया जाए या ऐसे Converter क्लास कंस्ट्रक्टर का उपयोग किया जाए जो लोड विकल्प स्वीकार करता है।

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

लोड विकल्पों और अन्य कंस्ट्रक्टर ओवरलोड्स के उपयोग के बारे में अधिक विवरण के लिए [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) देखें।
