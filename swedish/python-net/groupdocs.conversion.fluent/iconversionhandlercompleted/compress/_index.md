---
title: "compress‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Komprimerar konverteringsresultaten och returnerar en fortsättning som går vidare till Convert."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Komprimerar konverteringsresultaten och returnerar en fortsättning som går vidare till `Convert`.

Registrera en komprimerad‑ström‑hanterare i inträdesstadiet via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (inställning `OnCompressionCompleted`) snarare än att använda den föråldrade flödesskedje‑metoden på det returnerade gränssnittet.

```python
def compress(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Komprimeringskonverteringsalternativ. |

**Returns:** Continuation that proceeds to `Convert`.

### Se även
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
