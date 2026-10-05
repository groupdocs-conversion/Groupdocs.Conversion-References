---
title: "طريقة on_conversion_failed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل الصفحة."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل الصفحة.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – إجراء لمعالجة الفشل، يستقبل سياق الصفحة المحوَّلة والاستثناء الذي تسبب في الفشل. |

**Returns:** IConversionByPageHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### انظر أيضًا
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
