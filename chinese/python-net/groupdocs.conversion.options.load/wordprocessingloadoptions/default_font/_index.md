---
title: "default_font 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "WordProcessing 文档的默认字体。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

WordProcessing 文档的默认字体。

注意：替换顺序如下：
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def default_font(self):
    ...
@default_font.setter
def default_font(self, value):
    ...
```

### 另见
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
