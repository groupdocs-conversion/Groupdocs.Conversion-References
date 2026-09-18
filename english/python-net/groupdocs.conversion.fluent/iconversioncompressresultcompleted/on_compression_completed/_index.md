---
title: on_compression_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Receives the compressed document stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Receives the compressed document stream.

Fires only if `Compress(CompressionConvertOptions)` is set.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Compressed document stream callback. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
