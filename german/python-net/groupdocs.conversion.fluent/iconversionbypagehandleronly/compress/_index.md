---
title: "compress Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Komprimiert die Konvertierungsergebnisse; registrieren Sie einen komprimierten‑Stream‑Handler in der Einstiegsebene über IConversionSettings.withevents (Einstellung OnCompressionCompleted), anstatt die veraltete Fluent‑Kette zu verwenden…"
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimiert die Konvertierungsergebnisse; registrieren Sie einen komprimierten‑Stream‑Handler in der Einstiegsebene über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (Einstellung `OnCompressionCompleted`) anstatt die veraltete fluente Kettenmethode zu verwenden.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimierungs‑Konvertierungsoptionen. |

**Returns:** Continuation that proceeds to `Convert`.

### Siehe auch
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
