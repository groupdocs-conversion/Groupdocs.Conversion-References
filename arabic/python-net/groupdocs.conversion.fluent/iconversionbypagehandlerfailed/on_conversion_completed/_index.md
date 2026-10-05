---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل ردًا استدعائيًا يتم استدعاؤه عندما يكتمل تحويل الصفحة بنجاح."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

يسجل ردًا استدعائيًا يتم استدعاؤه عندما يكتمل تحويل الصفحة بنجاح.

إعادة الاستدعاء تستبدل أي معالج تم تعيينه مسبقًا.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | إجراء لمعالجة الانتهاء، يتلقى سياق الصفحة المحوّلة. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### انظر أيضًا
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
