---
title: "طريقة on_compression_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يتلقى تدفق مستند مضغوط."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

يتلقى تدفق المستند المضغوط. يتم تشغيله فقط إذا تم تعيين `Compress(CompressionConvertOptions)`.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | استدعاء رد فعل لتدفق المستند المضغوط. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
