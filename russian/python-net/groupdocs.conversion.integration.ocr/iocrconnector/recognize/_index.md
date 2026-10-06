---
title: "метод recognize"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Выполняет OCR‑обработку изображения, предоставленного в виде потока."
type: docs
url: /ru/python-net/groupdocs.conversion.integration.ocr/iocrconnector/recognize/
is_root: false
weight: 1010
---


## recognize {#image_stream}

Выполняет OCR‑обработку изображения, предоставленного в виде потока.

```python
def recognize(self, image_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Поток, содержащий изображение для обработки |

**Returns:** Structured recognized text, containing lines, words and their bounding rectangles.

### См. также
* class [`IOcrConnector`](/conversion/python-net/groupdocs.conversion.integration.ocr/iocrconnector/)
