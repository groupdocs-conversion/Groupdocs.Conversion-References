---
title: "recognize 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "스트림으로 제공된 이미지에 대한 OCR 처리를 수행합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.integration.ocr/iocrconnector/recognize/
is_root: false
weight: 1010
---


## recognize {#image_stream}

스트림으로 제공된 이미지에 대한 OCR 처리를 수행합니다.

```python
def recognize(self, image_stream):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | 스트림, 처리할 이미지를 포함합니다 |

**Returns:** Structured recognized text, containing lines, words and their bounding rectangles.

### 또 보기
* class [`IOcrConnector`](/conversion/python-net/groupdocs.conversion.integration.ocr/iocrconnector/)
