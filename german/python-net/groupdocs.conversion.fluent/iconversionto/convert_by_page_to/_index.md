---
title: "convert_by_page_to Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertierte Seite als Stream speichern."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionto/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Konvertierte Seite als Stream speichern.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Provider für den Stream der konvertierten Dokumentenseite. converted_stream_provider arg1arg1: Der Speicherkontext. |

**Returns:** Page options or handler setup interface to continue conversion building.

### Siehe auch
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
