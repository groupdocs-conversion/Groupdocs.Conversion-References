---
title: "पासवर्ड‑सुरक्षित फ़ाइल लोड करें"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Conversion for Python via .NET में Converter कंस्ट्रक्टर को पासवर्ड एट्रिब्यूट के साथ LoadOptions इंस्टेंस पास करके पासवर्ड‑सुरक्षित Word, Excel, PowerPoint, और PDF दस्तावेज़ों को अनलॉक और रूपांतरित करें।"
type: docs
url: /hi/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


*GroupDocs.Conversion for Python via .NET* के साथ आप पासवर्ड से सुरक्षित दस्तावेज़ों को लोड और रूपांतरित कर सकते हैं। यह सुविधा तब उपयोगी होती है जब आपको उन दस्तावेज़ों को संभालना हो जिनके सामग्री तक पहुँचने के लिए प्रमाणीकरण आवश्यक है।

पासवर्ड‑सुरक्षित दस्तावेज़ को लोड और रूपांतरित करने के लिए, नीचे दिए गए कोड उदाहरण में वर्णित चरणों का पालन करें:

{{< tabs \"code-example\">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # फ़ाइल पथ सेट करें
    file_path = "./password-protected.docx"
    
    # लोड विकल्प बनाएं और पासवर्ड सेट करें
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # स्रोत फ़ाइल स्ट्रीम और लोड विकल्प निर्दिष्ट करें
    converter = Converter(file_path, wp_load_options)
    
    # आउटपुट फ़ाइल स्थान और कन्वर्ज़न विकल्प निर्दिष्ट करें
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # कन्वर्ट करें और आउटपुट पथ पर सहेजें
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) पर क्लिक करें।

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

यदि प्रदान किया गया पासवर्ड गलत है, तो एक रनटाइम त्रुटि उत्पन्न होगी। अपेक्षित त्रुटि और त्रुटि संदेश इस प्रकार हैं:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: पासवर्ड-संरक्षित दस्तावेज़ के लिए फ़ाइल पथ निर्दिष्ट किया गया है। इस उदाहरण में, यह मानता है कि दस्तावेज़ का नाम `password-protected.docx` है।

2. **Load Options**: एक instance of [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) बनाया गया है, और दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड सेट किया गया है।

3. **Converter Initialization**: फ़ाइल पथ और पासवर्ड शामिल करने वाले लोड विकल्पों का उपयोग करके एक [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instance बनाया गया है।

4. **Convert Options**: परिवर्तन प्रक्रिया के लिए एक instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) बनाया गया है। यदि आवश्यक हो, तो आप परिणामी PDF के लिए आउटपुट पासवर्ड भी सेट कर सकते हैं।

4. **Conversion Execution**: अंत में, पासवर्ड-संरक्षित दस्तावेज़ को परिवर्तित करने और इसे PDF के रूप में सहेजने के लिए [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instance पर `convert` मेथड को कॉल किया जाता है।

### Conclusion

यह उदाहरण दिखाता है कि GroupDocs.Conversion for Python API का उपयोग करके पासवर्ड-संरक्षित दस्तावेज़ों को कैसे कुशलतापूर्वक लोड और परिवर्तित किया जाए। कोड चलाने से पहले पासवर्ड और फ़ाइल पथ को अपने वास्तविक मानों से बदलना सुनिश्चित करें।
