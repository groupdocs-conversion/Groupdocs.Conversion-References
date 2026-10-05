---
title: "طريقة on_conversion_failed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل المستند."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

يسجل رد نداء يتم استدعاؤه عندما يفشل تحويل المستند. إعادة الاستدعاء تستبدل أي معالج تم تعيينه مسبقًا.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | قابل للاستدعاء[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – إجراء لمعالجة الفشل، يتلقى سياق التحويل والاستثناء الذي تسبب في الفشل. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### انظر أيضًا
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
