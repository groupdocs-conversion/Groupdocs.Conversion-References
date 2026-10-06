---
title: "with_options‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ställer in konverteringsalternativ."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
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

Ställer in konverteringsalternativ.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Konverteringsalternativ. `ConvertContext` skickas till leverantören. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
