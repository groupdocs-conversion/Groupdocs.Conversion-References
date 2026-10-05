---
title: "فئة WordProcessingConvertOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "خيارات التحويل إلى نوع ملف معالجة نصية."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

خيارات التحويل إلى نوع ملف معالجة نصية.

يعرض نوع WordProcessingConvertOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | ينشئ مثيلاً جديدًا من [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | دقة DPI للصفحة المطلوبة بعد التحويل. الدقة الافتراضية هي 96 dpi. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | حجم الصفحة الاحتياطي. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | نوع الملف المطلوب تحويل المستند الإدخالي إليه. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | إعدادات الهوامش للتحويل، ممثلة بـ [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | خيارات تحويل Markdown. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | إعدادات الاتجاه. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | رقم الصفحة التي يبدأ التحويل منها. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | قائمة فهارس الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | عدد الصفحات التي سيتم تحويلها بدءًا من `PageNumber`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | كلمة المرور المستخدمة لحماية المستند المحول. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | وضع التعرف على PDF المستخدم للتحويل، مع تنفيذ [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/). |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | خيارات التحويل الخاصة بـ RTF. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | إعدادات الحجم للتحويل. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | خيارات العلامة المائية المحددة. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | مستوى التكبير بالنسبة المئوية. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Guides
أدلة المهام التي تستخدم `WordProcessingConvertOptions`:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### انظر أيضًا
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
