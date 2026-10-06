---
title: "font_substitutes プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "WordProcessing ドキュメントを変換する際に使用されるフォント代替です。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

WordProcessing ドキュメントを変換する際に使用されるフォント代替です。

注: 置換の順序は以下の通りです:

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

### 関連項目
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
