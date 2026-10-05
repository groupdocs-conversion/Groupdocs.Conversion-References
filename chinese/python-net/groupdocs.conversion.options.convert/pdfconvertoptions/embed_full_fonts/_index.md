---
title: "embed_full_fonts 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "此属性决定是否将完整字体文件嵌入 PDF，而不是子集。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/
is_root: false
weight: 2020
---


## embed_full_fonts property

此属性决定是否将完整字体文件嵌入 PDF，而不是子集。

设置为 True 时，输出文件大小会增加，但可确保在编辑生成的 PDF 时具有更好的兼容性。仅在从 WordProcessing 文档转换时适用。

### Definition:
```python
@property
def embed_full_fonts(self):
    ...
@embed_full_fonts.setter
def embed_full_fonts(self, value):
    ...
```

### 另见
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
