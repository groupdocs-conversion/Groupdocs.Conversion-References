---
title: "on_compression_completed メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "圧縮されたドキュメントストリームを受け取ります。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

圧縮されたドキュメントストリームを受け取ります。`Compress(CompressionConvertOptions)` が設定されている場合にのみ発生します。

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | 圧縮されたドキュメントストリームのコールバック。 |

**Returns:** Interface to continue conversion building.

### 関連項目
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
