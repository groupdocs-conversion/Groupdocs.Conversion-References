---
title: "__init__ 构造函数"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "初始化一个新的 PdfConvertOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) 实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 另见
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
