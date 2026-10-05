---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Empfängt den konvertierten Dokumenten‑Stream und wird nur ausgelöst, wenn ConvertTo(string fileName) oder ConvertTo(convertedStreamProvider) gesetzt ist."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Empfängt den konvertierten Dokumenten-Stream und wird nur ausgelöst, wenn `ConvertTo(string fileName)` oder `ConvertTo(convertedStreamProvider)` festgelegt ist.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Provider für den konvertierten Dokumenten‑Stream. |

**Returns:** Interface to continue conversion building.

### Siehe auch
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
