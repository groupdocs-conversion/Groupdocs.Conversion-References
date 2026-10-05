---
title: "خاصية attachment_content_handler"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "المندوب المستخدم لمعالجة مرفقات البريد الإلكتروني بشكل مخصص."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

المندوب المستخدم لمعالجة مرفقات البريد الإلكتروني بشكل مخصص.

يتلقى المفوض اسم المرفق (`str`)، نوع المحتوى (`str`)، وتدفق المرفق الأصلي (`io.RawIOBase`)، ويجب أن يُعيد تدفق مرفق مُعدَّل (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### انظر أيضًا
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
