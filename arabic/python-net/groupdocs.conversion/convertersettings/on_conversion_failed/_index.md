---
title: "خاصية on_conversion_failed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "معالج الحدث المستدعى عندما يفشل التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

معالج الحدث المستدعى عندما يفشل التحويل.

مُحترم لتوافق الإصدارات السابقة: يتم دمج القيمة في حقيبة الأحداث الداخلية عند إنشاء [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (مع الإشارة إلى [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) ويتم استبدالها إذا تم تعيين نفس المعالج أيضًا في معامل المُنشئ `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### انظر أيضًا
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
