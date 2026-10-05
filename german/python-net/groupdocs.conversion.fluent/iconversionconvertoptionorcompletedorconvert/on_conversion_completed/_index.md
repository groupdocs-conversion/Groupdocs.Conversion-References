---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Empfängt den konvertierten Dokumenten-Stream."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Empfängt den konvertierten Dokumenten‑Stream. Wird nur aufgerufen, wenn `ConvertTo(string fileName)` oder `ConvertTo(convertedStreamProvider)` konfiguriert wurde.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Anbieter für den konvertierten Dokumenten‑Stream. Der Anbieter erhält ein `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### Siehe auch
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
