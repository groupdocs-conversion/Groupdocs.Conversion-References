---
title: "with_options‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ställer in konverteringsalternativ för konverteringsprocessen."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Ställer in konverteringsalternativ för konverteringsprocessen.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Konverteringsalternativ. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Ställer in konverteringsalternativ med en leverantörsfunktion.

```python
def with_options(self, options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | En funktion som tillhandahåller konverteringsalternativ baserat på konverteringskontexten. |

**Returns:** Handler setup interface to continue conversion building.

### Se även
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
