---
title: "cap_resolution_to_page_content プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このプロパティは、ページごとの PDF レンダリング解像度をページの元のラスタ解像度に制限し、埋め込み画像より高い DPI でのレンダリングを防ぎ、ページを元の（小さい）解像度で出力します…"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

このプロパティは、ページごとの PDF レンダリング解像度をページのネイティブラスタ解像度に制限し、埋め込まれた画像より高い DPI でのレンダリングを防ぎ、最終出力ではページをネイティブ（小さい）ピクセルサイズと DPI で出力します。

画像主体（スキャン）ページのみが対象です；テキストやベクターコンテンツを含むページは決してソフト化されず、要求された DPI で出力されます。明示的な出力 [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) または [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) が設定されている場合、上限は無視されます。デフォルトは False（上限なし；すべてのページが要求された DPI でレンダリングおよび出力されます）。

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### 関連項目
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
