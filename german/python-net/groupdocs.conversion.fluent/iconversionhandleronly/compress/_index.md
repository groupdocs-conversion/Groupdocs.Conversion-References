---
title: "compress Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Komprimiert die Ergebnisse der Konvertierung."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimiert die Ergebnisse der Konvertierung.

Registrieren Sie einen komprimierten Stream‑Handler in der Einstieg‑Phase über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (Einstellung `OnCompressionCompleted`) anstatt über die veraltete Fluent‑Ketten‑Methode auf dem zurückgegebenen Interface.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimierungs‑Konvertierungsoptionen |

**Returns:** Continuation that proceeds to `Convert`.

### Siehe auch
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
