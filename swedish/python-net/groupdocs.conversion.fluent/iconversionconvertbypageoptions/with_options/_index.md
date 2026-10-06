---
title: "with_options‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ställer in konverteringsalternativ."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Ställer in konverteringsalternativ.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Konverteringsalternativ |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Ställ in konverteringsalternativ.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Konverteringsalternativ. Den anropbara tar emot ett `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/)
