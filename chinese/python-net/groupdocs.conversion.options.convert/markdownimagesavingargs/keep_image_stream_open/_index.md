---
title: "keep_image_stream_open 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性决定转换后转换器是否保持图像流打开。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

该属性决定转换后转换器是否保持图像流打开。

当为 False（默认）时，转换器在写入后关闭 [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) —— 这符合应刷新到磁盘的 `io.RawIOBase` 替代品的惯用做法。将其设为 True 可在转换完成后保持流打开（通常用于您自行读取的 `io.BytesIO`）；此后调用方负责释放。

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### 另见
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
