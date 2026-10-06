---
title: "layout_names プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換対象のレイアウト名。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

変換対象のレイアウト名。

PDF/UA-1 に変換する際には尊重されません。そのターゲットは図面を単一のタグ付けページとしてレンダリングし、選択されたレイアウトごとにシートを保持できないため、代わりに図面全体が変換され、ここでの設定は適用されません。

PDF を含む他のすべてのターゲットは選択を尊重します。これらのターゲットでは、名前は図面が持つレイアウトと完全に一致させて照合されるため、大文字小文字の違いだけの名前は別の名前として扱われます。何にも一致しない名前は除外され、呼び出し元にはそのシートだけが課金されます。何も一致しない名前があるリストは、`InvalidLoadOptionsException` をスローして、見つからなかった名前と図面が保持しているレイアウトを示し、呼び出し元が要求しなかったシートをレンダリングしません。レイアウトを全く持たない図面は例外となります。名前が一致する対象がないため、何も拒否されません。

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### 関連項目
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
