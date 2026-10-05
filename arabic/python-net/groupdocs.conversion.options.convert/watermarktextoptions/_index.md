---
title: "الفئة WatermarkTextOptions"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "خيارات ضبط علامة مائية نصية على المستند المحول."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

خيارات ضبط علامة مائية نصية على المستند المحول.

يمثل تكوين مظهر العلامة المائية. يمكن تكوين الخصائص التالية:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

يعرض نوع WatermarkTextOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | ينشئ مثيلاً من WatermarkTextOptions بالنص المحدد للعلامة المائية. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | استنساخ المثيل الحالي. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | يحدد ما إذا كان مثيلان لكائنين متساويين. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | يعمل كدالة التجزئة الافتراضية. (موروث من [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | لون خط العلامة المائية إذا تم تطبيق علامة مائية نصية. |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | نص العلامة المائية. |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | خط العلامة المائية المستخدم عند تطبيق علامة مائية نصية. |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | يتم تحجيم العلامة المائية تلقائيًا لتناسب حجم الصفحة عند تعيينها إلى True. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | يتم وضع العلامة المائية كخلفية؛ إذا كان True، تُوضع في الأسفل، وإلا تُوضع في الأعلى (القيمة الافتراضية هي False). (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | ارتفاع العلامة المائية. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | موضع العلامة المائية من اليسار. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | زاوية دوران العلامة المائية. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | موضع العلامة المائية من الأعلى. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | شفافية العلامة المائية. قيمة بين 0 و 1. القيمة 0 تعني مرئية بالكامل، والقيمة 1 تعني غير مرئية. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | عرض العلامة المائية. (موروث من [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |

### مثال

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
أدلة المهام التي تستخدم `WatermarkTextOptions`:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### انظر أيضًا
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
