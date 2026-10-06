---
title: "convert メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換チェーンを実行します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/convert/
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

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### 関連項目
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
