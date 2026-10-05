---
title: "طريقة on_conversion_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "استلام تدفق الصفحة المحولة."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

استلام تدفق الصفحة المحولة. سيتم إطلاقه فقط إذا تم تعيين `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | موفر تدفق الصفحة المحولة converted_page_stream arg1arg1: الـ `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### انظر أيضًا
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
