---
title: "طريقة with_options"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضبط خيارات التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/with_options/
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

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

اضبط خيارات التحويل.

```python
def with_options(self, convert_options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | مُزود خيارات التحويل. convert_options_provider arg1arg1: الـ `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
