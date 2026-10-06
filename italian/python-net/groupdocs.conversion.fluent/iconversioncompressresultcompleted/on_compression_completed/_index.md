---
title: "Metodo on_compression_completed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Riceve lo stream del documento compresso."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Riceve lo stream del documento compresso.

Viene attivato solo se `Compress(CompressionConvertOptions)` è impostato.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Callback dello stream di documento compresso. |

**Returns:** Interface to continue conversion building.

### Vedi anche
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
