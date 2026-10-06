---
title: "on_font_substituted プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ソース文書で参照されているフォントが利用できず、置き換えられたときに発生するイベント（顧客提供の FontSubstitute ルール、設定されたデフォルトフォント、または …）。"
type: docs
url: /ja/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

ソースドキュメントで参照されているフォントが利用できず、置き換えられたときに発生するイベント（顧客提供の[`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) ルール、設定されたデフォルトフォント、または変換パイプラインの内部フォールバックのいずれかによる）。

このイベントは単一の `Converter.Convert(...)` 呼び出し内で `(SourceFileName, OriginalFontName)` ごとに重複除外されます — 購読者はソース文書ごとに欠落フォントにつき最大で1つの通知を受け取ります。変換スレッド上で同期的に発生します。画像変換では発生しません。

プレゼンテーション文書の場合、フォント置換は Windows のみで検出されます。エンジンは他のオペレーティングシステムでは利用できないプラットフォーム固有のフォントマッチングを通じて解決するためです。

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### 関連項目
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
