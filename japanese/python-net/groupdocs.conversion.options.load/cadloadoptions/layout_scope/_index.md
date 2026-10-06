---
title: "layout_scope プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換される図面スペースを決定するレイアウトスコープ。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

変換される描画スペースを決定するレイアウトスコープ。デフォルトは[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)で、変換を制限しません。[`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) が指定されている場合は無視されます。これは、明示的なレイアウト名が常に優先されるためです。`None` 値は[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) とみなされます。

スコープが図面で提供されているシートのいずれも選択しない場合、変換は `InvalidLoadOptionsException` で失敗し、除外されたスペースを描画する代わりにスコープと利用可能なシートの名前が示されます。シートを全く提供しない図面は影響を受けず、単一ユニットとして変換されます。PDF/UA-1 への変換時には適用されません。その理由は [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) に記載されています。

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### 関連項目
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
