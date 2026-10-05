---
title: "طريقة on_conversion_failed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يفشل تحويل الصفحة."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

يسجل ردًا استدعائيًا يتم استدعاؤه عندما تفشل تحويل الصفحة. يعيد الاستدعاء استبدال أي معالج تم تعيينه مسبقًا.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | قابل للاستدعاء يتعامل مع الفشل، يتلقى سياق الصفحة المحوّلة والاستثناء الذي تسبب في الفشل. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### انظر أيضًا
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
