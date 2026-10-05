---
title: "طريقة on_conversion_failed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل رد نداء سيتم استدعاؤه عندما يفشل تحويل الصفحة، مع استبدال أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

يسجل رد نداء سيتم استدعاؤه عندما يفشل تحويل الصفحة، مع استبدال أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | قابل للاستدعاء يتعامل مع الفشل، يتلقى سياق الصفحة المحوّلة والاستثناء الذي تسبب في الفشل. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### انظر أيضًا
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
