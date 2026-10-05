---
title: "ImageConvertOptions فئة"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يمثل خيارات تحويل مستند إلى نوع ملف صورة."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

يمثل خيارات تحويل مستند إلى نوع ملف صورة.

نوع ImageConvertOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | يقوم بتهيئة نسخة جديدة من ImageConvertOptions. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | لون الخلفية لاستخدامه حيث يدعم تنسيق المصدر. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | ضبط سطوع الصورة. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | الخاصية تقيد دقة عرض PDF لكل صفحة إلى دقة الراستر الأصلية للصفحة، مما يمنع العرض بدقة DPI أعلى من الصورة المضمنة وإصدار الصفحة بأبعاد بكسل ودقة DPI الأصلية (الأصغر) في الناتج النهائي. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | ضبط التباين المطبق على الصورة. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | منطقة القص للصورة النقطية بعد التحويل. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | وضع انعكاس الصورة. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | نوع الملف المطلوب تحويل المستند الإدخالي إليه. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | تعديل غاما الصورة. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | الخيار الذي يحدد ما إذا كان سيتم تحويل الصورة إلى تدرج الرمادي. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | الارتفاع المطلوب للصورة بعد التحويل. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | الدقة الأفقية المطلوبة للصورة بعد التحويل؛ الافتراضي هو دقة ملف الإدخال أو 96 نقطة في البوصة. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | خيارات التحويل الخاصة بـ JPEG. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | الحد الأدنى لكل محور المطبق على DPI العرض المحدود عندما يكون [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) مفعلاً. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | رقم الصفحة التي يبدأ التحويل منها. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | قائمة فهارس الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | عدد الصفحات التي سيتم تحويلها بدءًا من `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | خيارات التحويل الخاصة بـ PSD. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | زاوية دوران الصورة. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | خيارات التحويل الخاصة بـ Tiff. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | خاصية UsePdf. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | الدقة العمودية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 نقطة في البوصة. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | خيارات العلامة المائية المحددة. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | خيارات التحويل الخاصة بـ WebP. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | العرض المطلوب للصورة بعد التحويل. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
دروس المهام التي تستخدم `ImageConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### انظر أيضًا
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
