---
title: "font_transformations 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在文档加载和字体替代后应用的字体转换，允许修改文档中的任何字体，包括已成功加载的字体。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_transformations/
is_root: false
weight: 2090
---


## font_transformations property

在文档加载和字体替代后应用的字体转换，允许修改文档中的任何字体，包括已成功加载的字体。

注意：字体转换在所有字体替换步骤完成后才会应用。

转换按它们在列表中出现的顺序处理。

使用场景：样式更改、品牌需求、可访问性改进。

### Definition:
```python
@property
def font_transformations(self):
    ...
@font_transformations.setter
def font_transformations(self, value):
    ...
```

### 另见
* class [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/)
