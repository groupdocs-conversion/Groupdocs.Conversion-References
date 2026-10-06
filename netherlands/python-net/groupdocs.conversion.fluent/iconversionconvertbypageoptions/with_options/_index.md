---
title: "with_options-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt conversie-opties in."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Stelt conversie-opties in.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Conversieopties |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Stel conversie-opties in.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Converteeropties. De callable ontvangt een `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Zie ook
* class [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/)
