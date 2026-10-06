---
title: "reason プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換パイプラインが報告した置換メッセージをそのまま、逐語的かつ未解析で提供します。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

変換パイプラインが報告した置換メッセージをそのまま、逐語的かつ未解析で提供します。

フォント名を構造的に公開するドキュメントの場合、これは None になる可能性があります（[`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) を使用してください）；それ以外の場合、欠落しているフォントと代替フォントの両方の名前を含む完全な人間可読の説明が格納されます。

### Definition:
```python
@property
def reason(self):
    ...
```

### 関連項目
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
