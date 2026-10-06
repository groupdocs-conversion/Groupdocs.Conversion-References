---
title: "with_options‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ställ in konverteringsalternativ."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Ställ in konverteringsalternativ.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Konverteringsalternativ |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Ställ in konverteringsalternativ.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Konvertera alternativ. `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
