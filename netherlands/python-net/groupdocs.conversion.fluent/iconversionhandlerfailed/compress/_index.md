---
title: "compress-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Comprimeert de conversieresultaten."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/compress/
is_root: false
weight: 1010
---


## compress {#options}

Comprimeert de conversieresultaten.

Registreer een gecomprimeerde‑streamhandler in de instapfase via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (instelling `OnCompressionCompleted`) in plaats van de verouderde fluent‑ketenmethode op de geretourneerde interface te gebruiken.

```python
def compress(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Compressie-conversieopties. |

**Returns:** Continuation that proceeds to `Convert`.

### Zie ook
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
