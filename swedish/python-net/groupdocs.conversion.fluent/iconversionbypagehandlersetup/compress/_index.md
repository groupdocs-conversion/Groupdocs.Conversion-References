---
title: "compress‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Komprimerar konverteringsresultaten med de angivna alternativen."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimerar konverteringsresultaten med de angivna alternativen.

Anropa den här metoden för att komprimera konverteringsresultaten. Registrera en komprimerad‑ström‑hanterare i inledningssteget via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (inställning `OnCompressionCompleted`) snarare än via den föråldrade flödessättnings‑kedjemetoden på det returnerade gränssnittet.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimeringskonverteringsalternativ. |

**Returns:** Continuation that proceeds to `Convert`.

### Se även
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
