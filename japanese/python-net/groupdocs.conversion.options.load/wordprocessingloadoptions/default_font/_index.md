---
title: "default_font プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "WordProcessing ドキュメントのデフォルトフォントです。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

WordProcessing ドキュメントのデフォルトフォントです。

注: 置換の順序は以下の通りです:
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

### 関連項目
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
