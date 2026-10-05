---
title: "طريقة on_conversion_failed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل المستند."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل المستند.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[`ConversionContext`, `Exception`], Any] – إجراء لمعالجة الفشل، يستقبل سياق التحويل والاستثناء الذي تسبب في الفشل. |

**Returns:** `IConversionHandlerOnly`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### انظر أيضًا
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
