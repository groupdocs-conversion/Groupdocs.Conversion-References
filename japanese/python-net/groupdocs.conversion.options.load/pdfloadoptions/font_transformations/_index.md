---
title: "font_transformations プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメントの読み込みとフォント置換の後に適用されるフォント変換で、読み込みに成功したフォントを含むドキュメント内の任意のフォントを変更できます。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_transformations/
is_root: false
weight: 2090
---


## font_transformations property

ドキュメントの読み込みとフォント置換の後に適用されるフォント変換で、読み込みに成功したフォントを含むドキュメント内の任意のフォントを変更できます。

注: フォント変換はすべてのフォント置換ステップが完了した後に適用されます。

変換はリストに表示されている順序で処理されます。

使用例: スタイルの変更、ブランド要件、アクセシビリティの改善。

### Definition:
```python
@property
def font_transformations(self):
    ...
@font_transformations.setter
def font_transformations(self, value):
    ...
```

### 関連項目
* class [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/)
