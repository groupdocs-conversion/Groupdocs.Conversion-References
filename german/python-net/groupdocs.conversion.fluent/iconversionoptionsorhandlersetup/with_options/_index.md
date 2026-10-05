---
title: "with_options Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Setzt Konvertierungsoptionen für den Konvertierungsprozess."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Setzt Konvertierungsoptionen für den Konvertierungsprozess.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Konversionsoptionen. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Setzt Konvertierungsoptionen mithilfe einer Provider-Funktion.

```python
def with_options(self, options_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Eine Funktion, die Konversionsoptionen basierend auf dem Konversionskontext bereitstellt. |

**Returns:** Handler setup interface to continue conversion building.

### Siehe auch
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
