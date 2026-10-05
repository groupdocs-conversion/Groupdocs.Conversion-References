---
title: "خاصية auto_detect_rtl_direction"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "خاصية autodetectrtldirection تحدد ما إذا كانت الفقرات والقطع التي تحتوي على نص يمين إلى يسار بشكل أساسي يتم إصلاح علامات bidi الخاصة بها قبل التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

تحدد الخاصية auto_detect_rtl_direction ما إذا كانت الفقرات والقطع التي تحتوي على نص من اليمين إلى اليسار بشكل أساسي يتم إصلاح أعلام bidi الخاصة بها قبل التحويل.

عند تعيينه إلى True (الافتراضي)، تقوم الخاصية بتطبيق خوارزمية تُستخدم من قبل Microsoft Word وLibreOffice، تُصحّح عرض مستندات العربية/العبرية التي تُنشئها أدوات مثل Google Docs والتي تُصدر OOXML بدون `<w:bidi/>` ومع `<w:rtl w:val="0"/>` على القطع التي تحتوي فقط على نص RTL. عيّن إلى False للحفاظ على التفسير الصارم لـ OOXML للعلامات المصدرية.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### انظر أيضًا
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
