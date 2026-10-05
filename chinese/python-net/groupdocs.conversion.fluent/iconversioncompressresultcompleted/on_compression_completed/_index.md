---
title: "on_compression_completed 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "接收压缩后的文档流。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

接收压缩后的文档流。

仅在设置了 `Compress(CompressionConvertOptions)` 时触发。

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | 压缩文档流回调。 |

**Returns:** Interface to continue conversion building.

### 另见
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
