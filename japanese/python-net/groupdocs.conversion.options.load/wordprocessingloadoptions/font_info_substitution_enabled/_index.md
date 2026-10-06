---
title: "font_info_substitution_enabled プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このフラグは、ドキュメント内の FontInfo に基づいて不足しているフォントの自動置換を有効にします。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

このフラグは、ドキュメント内の FontInfo に基づく欠損フォントの自動置換を有効にします。デフォルト: False.

注: 置換の順序は以下の通りです:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_info_substitution_enabled(self):
    ...
@font_info_substitution_enabled.setter
def font_info_substitution_enabled(self, value):
    ...
```

### 関連項目
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
