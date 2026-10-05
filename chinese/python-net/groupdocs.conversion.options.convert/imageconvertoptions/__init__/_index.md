---
title: "__init__ 构造函数"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "初始化一个新的 ImageConvertOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 ImageConvertOptions 实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### 另见
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
