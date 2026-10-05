---
title: "فئة ConverterSettings"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يحدد الإعدادات لتخصيص سلوك المحول."
type: docs
url: /ar/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

يحدد الإعدادات لتخصيص سلوك المحول.

يعرض نوع ConverterSettings الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | يُنشئ مثلاً جديداً من ConverterSettings بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج التحويل. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | مسارات دلائل الخطوط المخصصة. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل وتقدمه، مع تحويل ردود الاتصال Started و Progress و Completed إلى [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/)، [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/)، و [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) أثناء إنشاء [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | تنفيذ المسجل المستخدم لتسجيل عملية التحويل. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | معالج الحدث عند اكتمال الضغط. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | معالج الحدث المستدعى عندما يفشل التحويل حسب الصفحة. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | معالج الحدث المستدعى عندما يفشل التحويل. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | يقوم المحول بمسح دلائل الخطوط بشكل متكرر عندما تكون القيمة True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | المجلد المؤقت المستخدم للتحويل. |

### مثال

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### انظر أيضًا
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
