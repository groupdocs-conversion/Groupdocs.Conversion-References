---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يكتمل تحويل المستند بنجاح."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

يسجل ردًا استدعائيًا يتم استدعاؤه عندما يكتمل تحويل المستند بنجاح.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | إجراء لمعالجة الانتهاء، يتلقى سياق التحويل. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### انظر أيضًا
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
