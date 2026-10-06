---
title: "on_compression_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Ontvangt de gecomprimeerde documentstroom."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Ontvangt de gecomprimeerde documentstroom.

Wordt alleen geactiveerd als `Compress(CompressionConvertOptions)` is ingesteld.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Callback voor gecomprimeerde documentstroom. |

**Returns:** Interface to continue conversion building.

### Zie ook
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
