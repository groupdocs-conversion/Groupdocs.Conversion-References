---
title: "font_substitutes 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "转换 WordProcessing 文档时使用的字体替代。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

转换 WordProcessing 文档时使用的字体替代。

注意：替换顺序如下：

- 1) Automatically substitute missing fonts based on font name (if enabled).
- 2) Automatically substitute missing fonts based on FontConfig (if enabled).
- 3) Substitute missing fonts based on FontSubstitutes (if set).
- 4) Automatically substitute missing fonts based on FontInfo (if enabled).
- 5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### 另见
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
