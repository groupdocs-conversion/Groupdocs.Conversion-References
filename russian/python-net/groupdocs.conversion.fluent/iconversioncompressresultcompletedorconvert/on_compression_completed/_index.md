---
title: "метод on_compression_completed"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает поток сжатого документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

Получает поток сжатого документа. Срабатывает только если `Compress(CompressionConvertOptions)` установлен.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Обратный вызов потока сжатого документа. |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
