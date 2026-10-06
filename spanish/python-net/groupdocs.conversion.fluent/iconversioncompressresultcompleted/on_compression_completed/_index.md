---
title: "on_compression_completed método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recibe el flujo del documento comprimido."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Recibe el flujo del documento comprimido.

Se dispara solo si `Compress(CompressionConvertOptions)` está configurado.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Callback del flujo de documento comprimido. |

**Returns:** Interface to continue conversion building.

### Ver también
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
