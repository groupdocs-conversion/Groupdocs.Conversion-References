---
title: "recognize 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "对以流形式提供的图像执行 OCR 处理。"
type: docs
url: /zh/python-net/groupdocs.conversion.integration.ocr/iocrconnector/recognize/
is_root: false
weight: 1010
---


## recognize {#image_stream}

对以流形式提供的图像执行 OCR 处理。

```python
def recognize(self, image_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Stream，包含要处理的图像 |

**Returns:** Structured recognized text, containing lines, words and their bounding rectangles.

### 另见
* class [`IOcrConnector`](/conversion/python-net/groupdocs.conversion.integration.ocr/iocrconnector/)
