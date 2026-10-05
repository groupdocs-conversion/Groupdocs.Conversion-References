---
title: "طريقة with_options"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضبط خيارات التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/with_options/
is_root: false
weight: 1010
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

اضبط خيارات التحويل.

```python
def with_options(self, convert_options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | خيارات التحويل. الدالة القابلة للاستدعاء تستقبل `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/)
