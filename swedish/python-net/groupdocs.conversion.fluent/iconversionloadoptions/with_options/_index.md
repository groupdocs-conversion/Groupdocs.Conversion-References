---
title: "with_options‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Ställ in laddningsalternativ."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

Ställ in laddningsalternativ.

```python
def with_options(self, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| load_options | `LoadOptions` | Laddningsalternativ. |

## with_options {#load_options_provider}

Tillhandahåller laddningsalternativ för dokumentet som för närvarande laddas.

```python
def with_options(self, load_options_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Leverantör av laddningsalternativ. Leverantören får laddningsalternativskontexten. |

### Se även
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
