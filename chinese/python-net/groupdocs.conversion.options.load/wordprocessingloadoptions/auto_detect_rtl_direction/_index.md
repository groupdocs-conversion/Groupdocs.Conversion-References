---
title: "auto_detect_rtl_direction 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "autodetectrtldirection 属性决定在转换之前，段落和运行中主要为从右到左文本的双向标志是否被修复。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

auto_detect_rtl_direction 属性决定在转换之前，段落和运行的主要从右到左文本是否会修复其双向标志。

当设置为 True（默认）时，该属性应用 Microsoft Word 和 LibreOffice 使用的启发式方法，修复由 Google Docs 等工具生成的阿拉伯语/希伯来语文档的渲染问题，这些文档的 OOXML 中缺少 `<w:bidi/>` 且在仅包含 RTL 脚本的运行上使用 `<w:rtl w:val=\"0\"/>`。将其设置为 False 可保留源标记的严格 OOXML 解释。

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### 另见
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
