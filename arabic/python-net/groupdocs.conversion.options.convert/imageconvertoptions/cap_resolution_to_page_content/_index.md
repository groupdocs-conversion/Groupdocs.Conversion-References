---
title: "خاصية cap_resolution_to_page_content"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تقوم الخاصية بتحديد حد أقصى لدقة عرض PDF لكل صفحة إلى دقة الراستر الأصلية للصفحة، مما يمنع العرض بدقة DPI أعلى من الصورة المضمنة وإصدار الصفحة بدقتها الأصلية (الأصغر)…"
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

الخاصية تقيد دقة عرض PDF لكل صفحة إلى دقة الراستر الأصلية للصفحة، مما يمنع العرض بدقة DPI أعلى من الصورة المضمنة وإصدار الصفحة بأبعاد بكسل ودقة DPI الأصلية (الأصغر) في الناتج النهائي.

فقط الصفحات التي تهيمن عليها الصور (المسح) هي المتأثرة؛ الصفحات التي تحتوي على نص أو محتوى متجه لا تُنعم أبداً وتُصدر بدقة DPI المطلوبة. يتم تجاهل الحد عندما يتم تعيين إخراج صريح لـ [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) أو [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/). القيمة الافتراضية هي False (بدون تحديد حد؛ كل صفحة تُعرض وتُصدر بدقة DPI المطلوبة).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### انظر أيضًا
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
