---
title: "compress‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Komprimerar konverteringsresultaten."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimerar konverteringsresultaten.

Registrera en komprimerad‑ström‑hanterare i inledningssteget via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (inställning `OnCompressionCompleted`) snarare än via den föråldrade flödessättnings‑kedjemetoden på det returnerade gränssnittet.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimeringsalternativ för konvertering |

**Returns:** Continuation that proceeds to `Convert`.

### Se även
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
