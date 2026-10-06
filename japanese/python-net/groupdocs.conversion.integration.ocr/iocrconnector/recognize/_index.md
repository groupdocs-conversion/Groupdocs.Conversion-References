---
title: "recognize メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ストリームとして提供された画像の OCR 処理を実行します。"
type: docs
url: /ja/python-net/groupdocs.conversion.integration.ocr/iocrconnector/recognize/
is_root: false
weight: 1010
---


## recognize {#image_stream}

ストリームとして提供された画像の OCR 処理を実行します。

```python
def recognize(self, image_stream):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | 処理する画像を含むストリーム |

**Returns:** Structured recognized text, containing lines, words and their bounding rectangles.

### 関連項目
* class [`IOcrConnector`](/conversion/python-net/groupdocs.conversion.integration.ocr/iocrconnector/)
