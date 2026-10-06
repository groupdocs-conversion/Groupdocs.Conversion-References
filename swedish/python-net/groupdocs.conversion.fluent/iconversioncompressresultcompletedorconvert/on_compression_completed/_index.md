---
title: "on_compression_completed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tar emot en komprimerad dokumentström."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

Tar emot en komprimerad dokumentström. Utlöses endast om `Compress(CompressionConvertOptions)` är inställd.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Återanrop för komprimerad dokumentström. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
