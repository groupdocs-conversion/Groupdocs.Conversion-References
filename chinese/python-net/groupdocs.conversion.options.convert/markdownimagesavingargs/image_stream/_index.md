---
title: "image_stream 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "转换器将在此回调返回后写入图像字节的目标流。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/
is_root: false
weight: 2020
---


## image_stream property

转换器将在此回调返回后写入图像字节的目标流。

将其替换为您自己的可写流（例如，用于磁盘持久化的 `io.RawIOBase` 或您打算随后读取的 `io.BytesIO`）。

### Definition:
```python
@property
def image_stream(self):
    ...
@image_stream.setter
def image_stream(self, value):
    ...
```

### 另见
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
