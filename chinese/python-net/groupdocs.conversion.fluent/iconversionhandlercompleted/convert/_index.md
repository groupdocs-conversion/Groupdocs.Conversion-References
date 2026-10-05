---
title: "convert 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "执行转换链。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/
is_root: false
weight: 1030
---


## convert

执行转换链。

```python
def convert(self):
    ...
```

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### 另见
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
