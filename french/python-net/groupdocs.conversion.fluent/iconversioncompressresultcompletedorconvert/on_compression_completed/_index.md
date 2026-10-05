---
title: "Méthode on_compression_completed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Reçoit un flux de document compressé."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

Reçoit un flux de document compressé. Se déclenche uniquement si `Compress(CompressionConvertOptions)` est défini.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Rappel du flux de document compressé. |

**Returns:** Interface to continue conversion building.

### Voir aussi
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
