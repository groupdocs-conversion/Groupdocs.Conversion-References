---
title: "convert メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換チェーンを実行します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/
is_root: false
weight: 1030
---


## convert

変換チェーンを実行します。

```python
def convert(self):
    ...
```

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### 関連項目
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
