---
title: "detect_numbering_with_whitespaces 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性指定在将纯文本文档转换时如何识别编号列表项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

该属性指定在转换纯文本文档时如何识别编号列表项。默认值为 True。

如果此选项设置为 False，列表识别算法将在列表编号以点、右方括号或项目符号（如 "•", "*", "-" 或 "o"）结尾时检测列表段落。

如果此选项设置为 True，空格也会用作列表编号分隔符：阿拉伯式编号（例如 1., 1.1.2.）的列表识别算法同时使用空格和点（".")符号。

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### 另见
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
