---
title: "compress‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Komprimerar konverteringsresultaten."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimerar konverteringsresultaten.

Registrera en komprimerad‑ström‑hanterare i inledningsstadiet via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (inställning `OnCompressionCompleted`) snarare än den föråldrade fluent‑kedjemetoden på det returnerade gränssnittet.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimeringskonverteringsalternativ. |

**Returns:** Continuation that proceeds to `Convert`.

### Se även
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
