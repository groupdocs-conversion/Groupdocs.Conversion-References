---
title: "compress Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Komprimiert die Konvertierungsergebnisse."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimiert die Konvertierungsergebnisse.

Registrieren Sie einen komprimierten Stream‑Handler in der Eintrittsphase über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (Einstellung `OnCompressionCompleted`) anstatt der veralteten Fluent‑Ketten‑Methode auf der zurückgegebenen Schnittstelle.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimierungs‑Konvertierungsoptionen |

**Returns:** Continuation that proceeds to `Convert`.

### Siehe auch
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
