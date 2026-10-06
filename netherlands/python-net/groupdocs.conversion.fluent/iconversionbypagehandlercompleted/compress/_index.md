---
title: "compress-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Comprimeert de resultaten van de conversie."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprimeert de resultaten van de conversie.

Registreer een gecomprimeerde‑stream‑handler in de instapfase via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (instelling `OnCompressionCompleted`) in plaats van de verouderde fluent‑keten‑methode op de geretourneerde interface te gebruiken.

```python
def compress(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Compressie-conversieopties. |

**Returns:** Continuation that proceeds to `Convert`.

### Zie ook
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
