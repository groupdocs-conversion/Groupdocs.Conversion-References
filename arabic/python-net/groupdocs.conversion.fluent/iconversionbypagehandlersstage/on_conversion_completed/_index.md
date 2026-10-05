---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجل رد نداء سيتم استدعاؤه عندما تكتمل تحويل الصفحة بنجاح، مع استبدال أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

يسجل رد نداء سيتم استدعاؤه عندما تكتمل تحويل الصفحة بنجاح، مع استبدال أي معالج تم تعيينه مسبقًا عند إعادة الاستدعاء.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | إجراء لمعالجة الانتهاء، يتلقى سياق الصفحة المحوّلة. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### انظر أيضًا
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
