---
title: "خاصية listener"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل والتقدم، حيث يتم توجيه ردود النداء Started و Progress و Completed إلى ConversionEvents.onconversionstarted…"
type: docs
url: /ar/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل وتقدمه، مع تحويل ردود الاتصال Started و Progress و Completed إلى [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/)، [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/)، و [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) أثناء إنشاء [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### انظر أيضًا
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
