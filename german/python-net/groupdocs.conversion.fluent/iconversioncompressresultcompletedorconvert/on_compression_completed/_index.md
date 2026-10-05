---
title: "on_compression_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Empfängt einen komprimierten Dokumenten‑Stream."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

Empfängt einen komprimierten Dokumenten‑Stream. Wird nur ausgelöst, wenn `Compress(CompressionConvertOptions)` gesetzt ist.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Komprimierter Dokumentstrom-Callback. |

**Returns:** Interface to continue conversion building.

### Siehe auch
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
