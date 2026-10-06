---
title: "with_options-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stel conversie-opties in."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Stel conversie-opties in.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Conversieopties |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Stel conversie-opties in.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Conversie‑opties. De `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Zie ook
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
