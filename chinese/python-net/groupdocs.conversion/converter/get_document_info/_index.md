---
title: "get_document_info 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "检索源文档信息，包括页数和文件类型特定的其他属性。"
type: docs
url: /zh/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

检索源文档信息，包括页数和文件类型特定的其他属性。

了解更多关于已转换文档的信息——文件类型、页数、创建日期以及许多其他特定格式的属性：
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### 示例

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### 另见
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
