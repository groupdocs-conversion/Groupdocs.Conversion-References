---
title: "طريقة on_compression_completed"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يتلقى تدفق المستند المضغوط."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

يتلقى تدفق المستند المضغوط.

يتم إطلاقه فقط إذا تم تعيين `Compress(CompressionConvertOptions)`.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | استدعاء رد فعل لتدفق المستند المضغوط. |

**Returns:** Interface to continue conversion building.

### انظر أيضًا
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
