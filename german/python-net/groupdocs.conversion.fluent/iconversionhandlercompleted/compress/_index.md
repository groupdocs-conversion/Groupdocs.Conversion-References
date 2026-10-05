---
title: "compress Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Komprimiert die Konvertierungsergebnisse und gibt eine Fortsetzung zurück, die mit Convert fortfährt."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimiert die Konvertierungsergebnisse und gibt eine Fortsetzung zurück, die zu `Convert` fortschreitet.

Registrieren Sie einen komprimierten‑Stream‑Handler in der Einstiegsebene über [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (Einstellung `OnCompressionCompleted`), anstatt die veraltete Fluent‑Ketten‑Methode auf dem zurückgegebenen Interface zu verwenden.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimierungs‑Konvertierungsoptionen. |

**Returns:** Continuation that proceeds to `Convert`.

### Siehe auch
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
