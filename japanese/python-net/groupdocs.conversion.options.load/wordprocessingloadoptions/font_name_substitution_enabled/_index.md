---
title: "font_name_substitution_enabled プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このプロパティは、欠落したフォントがフォント名に基づいて自動的に置換されるかどうかを示します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

このプロパティは、フォント名に基づいて欠損フォントが自動的に置換されるかどうかを示します。デフォルト: False.

注: 置換の順序は以下の通りです:

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

### 関連項目
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
