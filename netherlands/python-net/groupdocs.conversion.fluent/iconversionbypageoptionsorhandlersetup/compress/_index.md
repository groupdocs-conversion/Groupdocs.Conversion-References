---
title: "compress-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Comprimeert de conversieresultaten."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprimeert de conversieresultaten.

Registreer een gecomprimeerde‑stream handler in de instapfase via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (instelling `OnCompressionCompleted`) in plaats van via de verouderde fluent chain methode op de geretourneerde interface.

```python
def compress(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Compressie converteeropties |

**Returns:** Continuation that proceeds to `Convert`.

### Zie ook
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
