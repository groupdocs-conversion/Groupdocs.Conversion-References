---
title: "compress Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Komprimiert die Konvertierungsergebnisse mit den angegebenen Optionen."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimiert die Konvertierungsergebnisse mit den angegebenen Optionen.

Rufen Sie diese Methode auf, um die Ergebnisse der Konvertierung zu komprimieren. Registrieren Sie einen komprimierten‑Stream‑Handler in der Einstiegsebene über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (Einstellung `OnCompressionCompleted`) anstatt über die veraltete Fluent‑Ketten‑Methode auf der zurückgegebenen Schnittstelle.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimierungs‑Konvertierungsoptionen. |

**Returns:** Continuation that proceeds to `Convert`.

### Siehe auch
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
