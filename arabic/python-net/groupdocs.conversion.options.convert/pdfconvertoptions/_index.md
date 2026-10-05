---
title: "الفئة PdfConvertOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "خيارات التحويل إلى نوع ملف PDF."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

خيارات التحويل إلى نوع ملف PDF.

نوع PdfConvertOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | يُنشئ مثلاً جديداً من [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | دقة DPI للصفحة المطلوبة بعد التحويل. الدقة الافتراضية هي 96 dpi. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | الخاصية تحدد ما إذا كان ملف الخط الكامل يُضمّن في ملف PDF بدلاً من مجموعة فرعية. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | حجم الصفحة الاحتياطي. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | نوع الملف المطلوب تحويل المستند الإدخالي إليه. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | إعدادات الهوامش المطبقة أثناء تحويل PDF. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | إعدادات الاتجاه. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | رقم الصفحة التي يبدأ التحويل منها. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | قائمة مؤشرات الصفحات التي سيتم تحويلها؛ حدّد لتحويل صفحات محددة. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | عدد الصفحات التي سيتم تحويلها بدءاً من `page_number`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | كلمة المرور المستخدمة لحماية المستند المحول. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | خيارات التحويل الخاصة بـ PDF. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | وضع إعادة التحجيم يحدد كيف يجب تحجيم المحتوى عندما يتغير حجم الصفحة. الوضع الافتراضي هو AlignTopLeft (بدون تحجيم). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | دوران الصفحة. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | إعدادات حجم الصفحة المستخدمة أثناء تحويل PDF. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | خيارات العلامة المائية المحددة. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
دروس المهام التي تستخدم `PdfConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### انظر أيضًا
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
