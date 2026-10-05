---
title: "त्वरित प्रारंभ गाइड"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक वर्चुअल एनवायरनमेंट सेट करें, groupdocs-conversion-net स्थापित करें, और पाँच मिनट से कम समय में तीन न्यूनतम उदाहरण चलाएँ — DOCX → PDF, PDF → प्रति-पृष्ठ PNG, और ZIP → समेकित PDF —।"
type: docs
url: /hi/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


यह गाइड GroupDocs.Conversion for Python को .NET के माध्यम से सेट अप करने और उपयोग शुरू करने का त्वरित अवलोकन प्रदान करता है। यह लाइब्रेरी डेवलपर्स को न्यूनतम कॉन्फ़िगरेशन के साथ विभिन्न फ़ाइल स्वरूपों (जैसे DOCX, PDF, PNG) के बीच परिवर्तित करने में सक्षम बनाती है।

## Prerequisites

आगे बढ़ने के लिए, सुनिश्चित करें कि आपके पास है:

1. **Configured** environment जैसा कि [System Requirements]() विषय में वर्णित है।
2. **Optionally** आप सभी उत्पाद सुविधाओं का परीक्षण करने के लिए [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) प्राप्त कर सकते हैं।

## Set Up Your Development Environment

सर्वोत्तम प्रथाओं के लिए, Python अनुप्रयोगों में निर्भरताओं को प्रबंधित करने के लिए एक वर्चुअल एनवायरनमेंट का उपयोग करें। वर्चुअल एनवायरनमेंट के बारे में अधिक जानने के लिए [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) दस्तावेज़ीकरण विषय देखें।

### Create and Activate a Virtual Environment

एक वर्चुअल एनवायरनमेंट बनाएं:

{{< tabs "example1">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

वर्चुअल एनवायरनमेंट सक्रिय करें:

{{< tabs "example2">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

वर्चुअल एनवायरनमेंट सक्रिय करने के बाद, पैकेज का नवीनतम संस्करण स्थापित करने के लिए अपने टर्मिनल में निम्न कमांड चलाएँ:

{{< tabs "example3">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

सुनिश्चित करें कि पैकेज सफलतापूर्वक स्थापित हो गया है। आपको संदेश दिखाई देना चाहिए

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

लाइब्रेरी को जल्दी से परीक्षण करने के लिए, चलिए एक DOCX फ़ाइल को PDF में परिवर्तित करते हैं। आप वह ऐप भी डाउनलोड कर सकते हैं जिसे हम बनाने वाले हैं [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip)।

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # लाइसेंस फ़ाइल का पूर्ण पथ प्राप्त करें
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # लाइसेंस बनाएं और पथ सेट करें
        license = License()
        license.set_license(license_path)

    # DOCX फ़ाइल लोड करें
    with Converter("./business-plan.docx") as converter:
        # परिवर्तन विकल्प बनाएं
        pdf_convert_options = PdfConvertOptions()

        # DOCX को PDF में परिवर्तित करें
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

आपकी फ़ोल्डर ट्री निम्नलिखित डायरेक्टरी संरचना जैसी दिखनी चाहिए:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

ऐप चलाने के बाद आप `deactivate` चलाकर या शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय कर सकते हैं।

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

इस उदाहरण में हम PDF दस्तावेज़ के पृष्ठों को PNG में बदलेंगे। आप वह ऐप जो हम बनाने वाले हैं, [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip) डाउनलोड कर सकते हैं।

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # लाइसेंस फ़ाइल का पूर्ण पथ प्राप्त करें
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # लाइसेंस बनाएं और पथ सेट करें
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # PDF दस्तावेज़ लोड करें
    with Converter("./annual-review.pdf") as converter:
        # स्रोत दस्तावेज़ में कुल पृष्ठों की संख्या निर्धारित करें
        pages_count = converter.get_document_info().pages_count

        # परिवर्तन विकल्प बनाएं और लूप के भीतर उनका पुन: उपयोग करें
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # प्रत्येक पृष्ठ को अलग PNG फ़ाइल में परिवर्तित करें
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "convert-pdf-pages-to-png-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

आपकी फ़ोल्डर ट्री निम्नलिखित डायरेक्टरी संरचना जैसी दिखनी चाहिए:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab "Windows" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

ऐप चलाने के बाद आप `deactivate` चलाकर या शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय कर सकते हैं।

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

इस उदाहरण में हम ZIP अभिलेख के सामग्री को PDF में बदलेंगे। GroupDocs.Conversion अभिलेख को खोलता है, अंदर की फ़ाइलों को परिवर्तित करता है, और एक एकीकृत PDF बनाता है जिसमें सभी परिवर्तित दस्तावेज़ शामिल होते हैं। आप वह ऐप जो हम बनाने वाले हैं, [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip) डाउनलोड कर सकते हैं।

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # लाइसेंस फ़ाइल का पूर्ण पथ प्राप्त करें
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # लाइसेंस बनाएं और पथ सेट करें
        license = License()
        license.set_license(license_path)

    # ZIP फ़ाइल लोड करें
    with Converter("./compressed.zip") as converter:
        # परिवर्तन विकल्प बनाएं
        pdf_convert_options = PdfConvertOptions()

        # आर्काइव निकालें, उसकी सामग्री को परिवर्तित करें, और एक एकीकृत PDF सहेजें
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) क्लिक करें।

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

आपकी फ़ोल्डर ट्री निम्नलिखित डायरेक्टरी संरचना जैसी दिखनी चाहिए:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_files_in_archive">}}
{{< tab "Windows" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

ऐप चलाने के बाद आप `deactivate` चलाकर या शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय कर सकते हैं।

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

बुनियादी बातें पूरी करने के बाद, अपने उपयोग को बेहतर बनाने के लिए अतिरिक्त संसाधनों का अन्वेषण करें:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
