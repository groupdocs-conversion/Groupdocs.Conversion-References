---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "新しい PdfConvertOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) インスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 関連項目
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
