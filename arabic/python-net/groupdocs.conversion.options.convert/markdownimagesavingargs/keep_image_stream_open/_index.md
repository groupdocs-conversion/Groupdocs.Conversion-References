---
title: "خاصية keep_image_stream_open"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تحدد الخاصية ما إذا كان المحول سيبقي تدفق الصورة مفتوحاً بعد التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

تحدد الخاصية ما إذا كان المحول سيبقي تدفق الصورة مفتوحاً بعد التحويل.

عند False (الافتراضي)، يغلق المحول [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) بعد الكتابة — وهو سلوك شائع لاستبدالات `io.RawIOBase` التي يجب تفريغها إلى القرص. اضبطه على True لإبقاء التدفق مفتوحًا بعد إكمال التحويل (عادةً لتدفق `io.BytesIO` الذي تنوي قراءته بنفسك)؛ يصبح المتصل مسؤولاً عن إغلاقه.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### انظر أيضًا
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
