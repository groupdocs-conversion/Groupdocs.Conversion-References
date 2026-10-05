---
title: "طريقة with_options"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضبط خيارات التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

يضبط خيارات التحويل.

```python
def with_options(self, convert_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options | `ConvertOptions` | خيارات التحويل |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

يضبط خيارات التحويل.

```python
def with_options(self, convert_options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | خيارات التحويل. يتم تمرير `ConvertContext` إلى الموفر. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
