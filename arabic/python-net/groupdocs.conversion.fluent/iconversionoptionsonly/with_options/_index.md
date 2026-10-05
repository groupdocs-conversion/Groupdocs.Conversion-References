---
title: "طريقة with_options"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضبط خيارات التحويل لعملية التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

يضبط خيارات التحويل لعملية التحويل.

```python
def with_options(self, convert_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options | `ConvertOptions` | خيارات التحويل. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

يضبط خيارات التحويل باستخدام دالة موفر.

```python
def with_options(self, options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | دالة توفر خيارات التحويل بناءً على سياق التحويل. |

**Returns:** Handler setup interface to continue conversion building.

### انظر أيضًا
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
