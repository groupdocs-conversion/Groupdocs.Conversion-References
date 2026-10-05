---
title: "font_name_substitution_enabled 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性指示是否根据字体名称自动替换缺失的字体。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

该属性指示是否基于字体名称自动替代缺失的字体。默认值：False。

注意：替换顺序如下：

- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_name_substitution_enabled(self):
    ...
@font_name_substitution_enabled.setter
def font_name_substitution_enabled(self, value):
    ...
```

### 另见
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
