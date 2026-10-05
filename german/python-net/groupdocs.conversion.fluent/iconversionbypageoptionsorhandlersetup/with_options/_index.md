---
title: "with_options Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertierungsoptionen festlegen."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Konvertierungsoptionen festlegen.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Konvertierungsoptionen |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Konvertierungsoptionen festlegen.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Konvertierungsoptionen. Der `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### Siehe auch
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
