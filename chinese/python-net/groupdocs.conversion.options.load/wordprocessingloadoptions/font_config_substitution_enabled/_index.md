---
title: "font_config_substitution_enabled 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性基于系统 FontConfig 启用缺失字体的自动替换。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

该属性基于系统 FontConfig 启用缺失字体的自动替代。默认值为 False。

注意：替换顺序如下：
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_config_substitution_enabled(self):
    ...
@font_config_substitution_enabled.setter
def font_config_substitution_enabled(self, value):
    ...
```

### 另见
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
