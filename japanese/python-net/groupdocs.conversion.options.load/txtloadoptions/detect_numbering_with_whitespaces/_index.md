---
title: "detect_numbering_with_whitespaces プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このプロパティは、プレーンテキストドキュメントが変換される際に番号付きリスト項目がどのように認識されるかを指定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

このプロパティは、プレーンテキストドキュメントを変換する際に番号付きリスト項目がどのように認識されるかを指定します。デフォルト値は True です。

このオプションが False に設定されている場合、リスト認識アルゴリズムはリスト番号がドット、右括弧、または箇条書き記号（例: "•", "*", "-", "o"）で終わるとリスト段落を検出します。

このオプションが True に設定されている場合、空白もリスト番号の区切りとして使用されます。アラビア式番号付け（例: 1., 1.1.2.）のリスト認識アルゴリズムは空白とドット（".") の両方を使用します。

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### 関連項目
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
