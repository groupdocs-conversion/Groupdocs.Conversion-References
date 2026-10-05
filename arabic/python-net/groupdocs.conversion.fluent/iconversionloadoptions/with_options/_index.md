---
title: "طريقة with_options"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تعيين خيارات التحميل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

تعيين خيارات التحميل.

```python
def with_options(self, load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| load_options | `LoadOptions` | خيارات التحميل. |

## with_options {#load_options_provider}

يوفر خيارات التحميل للمستند الذي يتم تحميله حاليًا.

```python
def with_options(self, load_options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | مزود خيارات التحميل. المزود يتلقى سياق خيارات التحميل. |

### انظر أيضًا
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
