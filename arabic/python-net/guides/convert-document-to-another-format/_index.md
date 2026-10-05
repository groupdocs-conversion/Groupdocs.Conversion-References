---
title: "تحويل مستند إلى تنسيق آخر"
linkTitle: "Convert to Another Format"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "قم بتحويل مستند واحد من تنسيق إلى آخر، مع إمكانية اختيار صفحات محددة أو نطاق صفحات باستخدام سمات pages / page_number / pages_count في ConvertOptions مع GroupDocs.Conversion للغة بايثون عبر .NET."
type: docs
url: /ar/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


يغطي موضوع الوثائق هذا تحويل مستند واحد إلى تنسيق آخر، حيث يتم إنتاج مستند واحد فقط كخرج. يوضح المخطط التالي عملية تحويل ملف من تنسيق إلى آخر:

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e.g. PDF)\"]

%% اتصالات الحواف بين العقد
A --> B --> C

لتحويل وحفظ مستند، استخدم طرق الفئة التالية [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) :

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

القائمة التالية من فئات [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) يمكن استخدامها لتحويل مستند إلى تنسيق إخراج واحد محدد:

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

المثال التالي يوضح كيفية تحويل ملف DOCX إلى PDF:

{{< tabs \"example-1\">}}
{{< tab \"convert_document_to_another_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # إنشاء كائن Converter باستخدام المستند الإدخالي 
    with Converter("./business-plan.docx") as converter:
        # إنشاء خيارات التحويل لتحديد تنسيق الإخراج
        pdf_convert_options = PdfConvertOptions()
        
        # تحويل المستند المدخل إلى PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) لتنزيله.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

بشكل افتراضي، كل فئة من فئات [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) لديها تنسيق هدف افتراضي خاص بها. على سبيل المثال، تنسيق الإخراج الافتراضي لـ [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) هو [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/).

لتعيين تنسيق إخراج مختلف ضمن عائلة التنسيقات، استخدم الخاصية `format`. يوضح المثال التالي كيفية تحديد تنسيق الهدف كـ `TXT` عند تحويل ملف `DOCX`:

{{< tabs \"example-2\">}}
{{< tab \"specify_output_format.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # إنشاء كائن Converter باستخدام المستند الإدخالي 
    with Converter("./business-plan.docx") as converter:
        # إنشاء خيارات التحويل لتحديد تنسيق الإخراج، بشكل افتراضي يكون DOCX
        word_convert_options = WordProcessingConvertOptions()
        # غيّر تنسيق الإخراج داخل عائلة التنسيقات من DOCX إلى TXT
        word_convert_options.format = WordProcessingFileType.TXT
        
        # حوّل المستند الإدخالي إلى TXT
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) لتنزيله.

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

اكتشف كيفية الحصول على عدد صفحات المستند في موضوع الوثائق [Getting Document Information]().

لتحويل صفحات مستند محددة، يمكنك استخدام الفئات التالية [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) التي توفر سمات `pages` و `page_number` و `pages_count`. تسمح لك هذه الخيارات بتحديد صفحات فردية أو نطاق من الصفحات للتحويل.

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

يمكنك تحديد صفحات المستند التي ترغب في تحويلها، كما هو موضح في المثال التالي:

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # إنشاء كائن Converter باستخدام المستند الإدخالي 
    with Converter("./business-plan.docx") as converter:
        # إنشاء خيارات التحويل لتحديد تنسيق الإخراج
        pdf_convert_options = PdfConvertOptions()
        # حدد صفحات المستند التي تريد تحويلها
        pdf_convert_options.pages = [1, 3, 5]

        # حوّل الصفحات المحددة من المستند الإدخالي إلى PDF
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) لتنزيله.

{{< /tab >}}
{{< tab \"pages-1-3-5.pdf\" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

كبديل، يمكنك تحديد عدد من الصفحات المتتالية للتحويل، كما هو موضح في المثال التالي:

{{< tabs \"example-4\">}}
{{< tab \"convert_consecutive_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # إنشاء كائن Converter باستخدام المستند الإدخالي 
    with Converter("./business-plan.docx") as converter:
        # إنشاء خيارات التحويل لتحديد تنسيق الإخراج
        pdf_convert_options = PdfConvertOptions()
        # حدد الصفحة البداية وعدد الصفحات للتحويل
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # حوّل النطاق المحدد من الصفحات في المستند إلى PDF
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) لتنزيله.

{{< /tab >}}
{{< tab \"pages-1-through-5.pdf\" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
