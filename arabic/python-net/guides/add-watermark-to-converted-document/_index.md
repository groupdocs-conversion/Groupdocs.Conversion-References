---
title: "إضافة علامة مائية إلى المستند المحوَّل"
linkTitle: "Add a Watermark"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "طبع علامة مائية نصية على كل صفحة من مستند محوَّل باستخدام GroupDocs.Conversion للـ Python عبر .NET — التحكم في اللون والحجم والموضع والدوران والشفافية، وكذلك وضعها في المقدمة أو الخلفية عبر WatermarkTextOptions."
type: docs
url: /ar/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


يوضح هذا الموضوع كيفية إضافة علامة مائية أثناء عملية التحويل باستخدام GroupDocs.Conversion للـ Python عبر .NET. يمكن تطبيق العلامة المائية على المستند أثناء تحويله إلى تنسيق آخر، مما يساعد على حماية المحتوى وضمان إمكانية التعرف عليه.

لتمكين إضافة العلامة المائية، يمكنك استخدام الخاصية `watermark` في الفئات المناسبة من [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). أدناه الفئات المدعومة من [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) التي تسمح لك بتكوين العلامة المائية أثناء التحويل:

هل تبحث عن قدرات متقدمة لإضافة العلامات المائية؟ بينما يقدم GroupDocs.Conversion إضافة علامات مائية أساسية، يمكنك استكشاف [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) للحصول على حل شامل مع ميزات محسّنة.

## Supported ConvertOptions Classes

الفئات التالية من [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) التي توفر الخاصية `watermark`.

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

يتم استخدام الفئة [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) لتكوين مظهر العلامة المائية. يمكن تكوين الخيارات التالية لإضافة علامة مائية:

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

يوضح المثال التالي كيفية تحويل مستند DOCX إلى PDF وإضافة علامة مائية:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # إنشاء كائن Converter باستخدام المستند الإدخالي 
    with Converter("./professional-services.docx") as converter:
        # إعداد خيارات العلامة المائية
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # إعداد خيارات التحويل
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # تنفيذ التحويل
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` هو الملف العيني المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) لتنزيله.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
