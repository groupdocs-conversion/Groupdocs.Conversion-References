---
title: "تحويل المستند إلى ملفات متعددة الصفحات"
linkTitle: "Convert Document To Multiple"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /ar/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: تحويل مستند إلى ملفات متعددة الصفحات
linkTitle: التحويل إلى ملفات متعددة
weight: 3
description: "قم بعرض كل صفحة من مستند متعدد الصفحات في ملف إخراج خاص بها — كرّر page_number مع pages_count=1 واستخدم Converter.convert() لإنتاج PNG أو PDF أو صورة واحدة لكل صفحة باستخدام GroupDocs.Conversion for Python عبر .NET."
keywords: التحويل إلى ملفات متعددة, إخراج لكل صفحة, page_number, pages_count, حلقة الصفحة, تحويل صفحات العرض التقديمي, تحويل صفحات PDF إلى PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

هذا الموضوع الوثائقي يغطي تحويل مستند متعدد الصفحات واحد إلى ملفات صفحات منفصلة. يوضح المخطط التالي عملية تحويل ملف متعدد الصفحات إلى صفحات منفصلة:

flowchart LR
%% Nodes
A["مستند الإدخال"]
B[\"Conversion\"]
C["صفحة محوّلة 1"]
D["صفحة محوّلة 2"]
E["صفحة محوّلة N"]

%% اتصالات الحواف بين العقد
A --> B --> C
B --> D
B --> E

لتحويل مستند إلى ملفات لكل صفحة، استخدم الطريقة `Converter.convert(file_path, convert_options)` مع الخصائص `page_number` و `pages_count` على الفئات المدعومة [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) :

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

لإنشاء ملف إخراج واحد لكل صفحة، كرّر من `1` إلى `converter.get_document_info().pages_count`، مع تحديث `page_number` في كل تكرار والكتابة إلى مسار إخراج مختلف. ضبط `pages_count = 1` يضمن أن كل استدعاء ينتج صفحة واحدة.

## Supported ConvertOptions Classes

الفئات التالية [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) تعرض الخصائص `page_number` و `pages_count` المستخدمة في هذا الموضوع:

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

المثال التالي يوضح كيفية تحويل كل شريحة في عرض PPTX إلى صورة PNG وحفظ صور الإخراج في مجلد محدد.
 
قالب اسم الملف لملفات الإخراج هو `converted-page-{page number}.{output file extension}`. في هذا المثال، سيتم حفظ الشريحة الأولى كـ `converted-page-1.png`.

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

    # إنشاء كائن Converter باستخدام المستند الإدخالي
    with Converter("./basic-presentation.pptx") as converter:
        # تحديد العدد الإجمالي للصفحات في المستند المصدر
        pages_count = converter.get_document_info().pages_count

        # أنشئ خيارات التحويل مرة واحدة وأعد استخدامها داخل الحلقة
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # تحويل كل صفحة إلى ملف PNG منفصل
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) لتنزيله.

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

اكتشف كيفية الحصول على عدد صفحات المستند في موضوع الوثائق [Getting Document Information]().

المثال التالي يوضح كيفية تحويل شريحة محددة في عرض PPTX وحفظها كملف منفصل.

{{< tabs \"example-2\">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # إنشاء كائن Converter باستخدام المستند الإدخالي
    with Converter("./basic-presentation.pptx") as converter:
        # إنشاء خيارات التحويل
        png_convert_options = ImageConvertOptions()
        # حدد تنسيق الإخراج كـ PNG
        png_convert_options.format = ImageFileType.PNG

        # حدد الصفحة الوحيدة للتحويل
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # احفظ الصفحة المحوّلة إلى ملف
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) لتنزيله.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

اكتشف كيفية الحصول على عدد صفحات المستند في موضوع الوثائق [Getting Document Information]().

إذا كنت بحاجة إلى الصفحة المحوّلة كذاكرة مؤقتة في الذاكرة (مثلاً، لإرسالها إلى واجهة برمجة تطبيقات أخرى دون لمس نظام الملفات لاحقًا)، قم بتحويل الصفحة إلى ملف أولاً ثم اقرأه في كائن `BytesIO`:

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

    # إنشاء كائن Converter باستخدام المستند الإدخالي
    with Converter("./basic-presentation.pptx") as converter:
        # إنشاء خيارات التحويل
        png_convert_options = ImageConvertOptions()
        # حدد تنسيق الإخراج كـ PNG
        png_convert_options.format = ImageFileType.PNG

        # حدد الصفحة الوحيدة للتحويل
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # حوّل واحفظ الصفحة إلى ملف على القرص
        converter.convert(output_file, png_convert_options)

    # حمّل الصفحة المحوّلة إلى تدفق في الذاكرة للاستخدام لاحقًا
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream الآن يحتوي على بايتات PNG ويمكن تمريره إلى أي مستهلك
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) لتنزيله.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
