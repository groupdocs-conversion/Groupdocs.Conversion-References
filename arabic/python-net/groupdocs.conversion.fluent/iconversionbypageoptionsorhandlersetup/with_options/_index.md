---
title: "طريقة with_options"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "اضبط خيارات التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

اضبط خيارات التحويل.

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
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | خيارات التحويل. الـ `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
