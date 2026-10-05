---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يتلقى تدفق الصفحة المحولة."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

يتلقى تدفق الصفحة المحولة. سيتم تشغيله فقط إذا تم تعيين `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | مُزود تدفق الصفحة المحوَّلة. الـ `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
