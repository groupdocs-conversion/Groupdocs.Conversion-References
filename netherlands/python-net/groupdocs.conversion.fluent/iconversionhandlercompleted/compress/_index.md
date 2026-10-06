---
title: "compress-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Comprimeert de conversieresultaten en retourneert een voortzetting die doorgaat naar Convert."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprimeert de conversieresultaten en retourneert een vervolg dat doorgaat naar `Convert`.

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
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
