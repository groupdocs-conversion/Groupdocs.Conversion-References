---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يتلقى تدفق المستند المحوَّل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

يتلقى تدفق المستند المحول. يتم استدعاؤه فقط عندما يتم تكوين `ConvertTo(string fileName)` أو `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | موفر لتدفق المستند المحول. الموفر يتلقى `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
