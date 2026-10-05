---
title: "convert_to Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertiertes Dokument als Datei speichern."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionto/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Konvertiertes Dokument als Datei speichern.

```python
def convert_to(self, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Konvertiertes Dokument |

**Returns:** Options or handler setup interface to continue conversion building

## convert_to {#converted_stream_provider}

Speichert das konvertierte Dokument als Stream.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Provider für den Stream des konvertierten Dokuments. Der Speicherkontext. |

**Returns:** Options or handler setup interface to continue conversion building.

### Siehe auch
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
