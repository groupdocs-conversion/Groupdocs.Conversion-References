---
title: "on_compression_completed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tar emot den komprimerade dokumentströmmen."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Tar emot den komprimerade dokumentströmmen.

Utlöses endast om `Compress(CompressionConvertOptions)` är inställt.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Återanrop för komprimerad dokumentström. |

**Returns:** Interface to continue conversion building.

### Se även
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
