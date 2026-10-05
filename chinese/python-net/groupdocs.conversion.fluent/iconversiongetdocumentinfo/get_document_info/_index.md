---
title: "get_document_info 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "检索源文档信息，包括页数以及文件类型特有的其他属性。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

检索源文档信息，包括页数以及文件类型特有的其他属性。

```python
def get_document_info(self):
    ...
```

### 示例

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### 另见
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
