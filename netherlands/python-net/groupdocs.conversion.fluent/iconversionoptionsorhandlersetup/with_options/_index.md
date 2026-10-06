---
title: "with_options-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt conversieopties in voor het conversieproces."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Stelt conversieopties in voor het conversieproces.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Conversie‑opties. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Stelt conversieopties in met behulp van een providerfunctie.

```python
def with_options(self, options_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Een functie die conversie‑opties levert op basis van de conversie‑context. |

**Returns:** Handler setup interface to continue conversion building.

### Zie ook
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
