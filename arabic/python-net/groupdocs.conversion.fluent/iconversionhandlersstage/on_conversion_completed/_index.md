---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجّل رد نداء يتم استدعاؤه عند إكمال تحويل المستند بنجاح، مستبدلاً أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

يسجّل رد نداء يتم استدعاؤه عند إكمال تحويل المستند بنجاح، مستبدلاً أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | إجراء لمعالجة الانتهاء، يتلقى سياق التحويل. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### انظر أيضًا
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
