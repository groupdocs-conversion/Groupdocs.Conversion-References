---
title: "with_options Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Setzt Konvertierungsoptionen."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

Setzt Konvertierungsoptionen.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Konvertierungsoptionen |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Setzt Konvertierungsoptionen.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Konvertierungsoptionen. Der `ConvertContext` wird an den Provider übergeben. |

**Returns:** Interface to continue conversion building.

### Siehe auch
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
