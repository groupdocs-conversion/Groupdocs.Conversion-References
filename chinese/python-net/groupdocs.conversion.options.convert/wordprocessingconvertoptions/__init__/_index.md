---
title: "__init__ 构造函数"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "初始化 WordProcessingConvertOptions 的新实例。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) 实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### 另见
* class [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)
