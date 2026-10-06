---
title: "on_compression_completed 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "압축된 문서 스트림을 받습니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

압축된 문서 스트림을 받습니다. `Compress(CompressionConvertOptions)`가 설정된 경우에만 발생합니다.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | 압축된 문서 스트림 콜백. |

**Returns:** Interface to continue conversion building.

### 또 보기
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
