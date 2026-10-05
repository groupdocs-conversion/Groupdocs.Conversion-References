---
title: "دليل البدء السريع"
linkTitle: "Quick Start Guide"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "قم بإعداد بيئة افتراضية، تثبيت groupdocs-conversion-net، وتشغيل ثلاثة أمثلة بسيطة — DOCX → PDF، PDF → PNG لكل صفحة، وZIP → PDF موحد — في أقل من خمس دقائق."
type: docs
url: /ar/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


يقدم هذا الدليل نظرة سريعة حول كيفية إعداد والبدء في استخدام GroupDocs.Conversion للبايثون عبر .NET. تمكّن هذه المكتبة المطورين من التحويل بين صيغ ملفات مختلفة (مثل DOCX، PDF، PNG) بأقل قدر من الإعداد.

## Prerequisites

للمتابعة، تأكد من أنك تمتلك:

1. بيئة **Configured** كما هو موضح في موضوع [System Requirements]().
2. **Optionally** يمكنك [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) لاختبار جميع ميزات المنتج.

## Set Up Your Development Environment

لأفضل الممارسات، استخدم بيئة افتراضية لإدارة الاعتمادات في تطبيقات بايثون. تعرف على المزيد حول البيئة الافتراضية في موضوع الوثائق [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

إنشاء بيئة افتراضية:

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

تفعيل بيئة افتراضية:

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

بعد تفعيل البيئة الافتراضية، نفّذ الأمر التالي في الطرفية لتثبيت أحدث نسخة من الحزمة:

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

تأكد من أن الحزمة تم تثبيتها بنجاح. يجب أن ترى الرسالة

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

لاختبار المكتبة بسرعة، دعنا نحول ملف DOCX إلى PDF. يمكنك أيضًا تنزيل التطبيق الذي سنقوم بإنشائه [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # احصل على المسار المطلق لملف الترخيص
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # إنشاء الترخيص وتعيين المسار
        license = License()
        license.set_license(license_path)

    # تحميل ملف DOCX
    with Converter("./business-plan.docx") as converter:
        # إنشاء خيارات التحويل
        pdf_convert_options = PdfConvertOptions()

        # تحويل DOCX إلى PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` هو ملف عينة يُستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) لتنزيله.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

يجب أن يبدو شجرة المجلدات الخاصة بك مشابهة للبنية الدليلية التالية:

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

بعد تشغيل التطبيق يمكنك إلغاء تنشيط البيئة الافتراضية بتنفيذ `deactivate` أو إغلاق الصدفة.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

في هذا المثال سنقوم بتحويل صفحات مستند PDF إلى PNG. يمكنك تنزيل التطبيق الذي سنبنيه [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # احصل على المسار المطلق لملف الترخيص
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # إنشاء الترخيص وتعيين المسار
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # تحميل مستند PDF
    with Converter("./annual-review.pdf") as converter:
        # تحديد العدد الإجمالي للصفحات في المستند المصدر
        pages_count = converter.get_document_info().pages_count

        # إنشاء خيارات التحويل وإعادة استخدامها داخل الحلقة
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # تحويل كل صفحة إلى ملف PNG منفصل
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` هو ملف عينة يُستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) لتنزيله.

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

يجب أن يبدو شجرة المجلدات الخاصة بك مشابهة للبنية الدليلية التالية:

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

بعد تشغيل التطبيق يمكنك إلغاء تنشيط البيئة الافتراضية بتنفيذ `deactivate` أو إغلاق الصدفة.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

في هذا المثال سنقوم بتحويل محتويات أرشيف ZIP إلى PDF. يفتح GroupDocs.Conversion الأرشيف، يحول الملفات الموجودة بداخله، وينتج ملف PDF موحد يحتوي على كل مستند تم تحويله. يمكنك تنزيل التطبيق الذي سنبنيه [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # احصل على المسار المطلق لملف الترخيص
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # إنشاء الترخيص وتعيين المسار
        license = License()
        license.set_license(license_path)

    # تحميل ملف ZIP
    with Converter("./compressed.zip") as converter:
        # إنشاء خيارات التحويل
        pdf_convert_options = PdfConvertOptions()

        # استخراج الأرشيف، تحويل محتوياته، وحفظ ملف PDF موحد
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` هو ملف عينة يُستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) لتنزيله.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

يجب أن يبدو شجرة المجلدات الخاصة بك مشابهة للبنية الدليلية التالية:

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

بعد تشغيل التطبيق يمكنك إلغاء تنشيط البيئة الافتراضية بتنفيذ `deactivate` أو إغلاق الصدفة.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

بعد إكمال الأساسيات، استكشف الموارد الإضافية لتعزيز استخدامك:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
