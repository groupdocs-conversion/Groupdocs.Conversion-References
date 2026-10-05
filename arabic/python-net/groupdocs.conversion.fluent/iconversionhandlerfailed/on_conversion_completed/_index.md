---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يكتمل تحويل المستند بنجاح."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

يسجّل رد نداء يتم استدعاؤه عند إكمال تحويل المستند بنجاح. إعادة الاستدعاء تستبدل أي معالج تم تعيينه مسبقًا.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | قابل للاستدعاء يتعامل مع الإكمال، ويتلقى سياق التحويل. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### انظر أيضًا
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
