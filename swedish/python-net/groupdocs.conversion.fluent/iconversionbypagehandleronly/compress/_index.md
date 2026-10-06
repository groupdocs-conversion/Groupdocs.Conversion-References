---
title: "compress‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Komprimerar konverteringsresultaten; registrera en komprimerad-ström-hanterare i inträdesstadiet via IConversionSettings.withevents (inställning OnCompressionCompleted) istället för att använda den föråldrade flödessättnings-metoden…"
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimerar konverteringsresultaten; registrera en komprimerad‑strömshanterare i ingångsstadiet via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (sätter `OnCompressionCompleted`) istället för att använda den föråldrade flytande kedjemetoden.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimeringskonverteringsalternativ. |

**Returns:** Continuation that proceeds to `Convert`.

### Se även
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
