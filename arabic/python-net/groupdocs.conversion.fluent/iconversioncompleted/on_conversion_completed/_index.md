---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يتلقى تدفق المستند المحول ويتم تشغيله فقط إذا تم تعيين ConvertTo(string fileName) أو ConvertTo(convertedStreamProvider)."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

يتلقى تدفق المستند المحول ويتم تشغيله فقط إذا تم تعيين `ConvertTo(string fileName)` أو `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | مزوّد تدفق المستند المحول. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
