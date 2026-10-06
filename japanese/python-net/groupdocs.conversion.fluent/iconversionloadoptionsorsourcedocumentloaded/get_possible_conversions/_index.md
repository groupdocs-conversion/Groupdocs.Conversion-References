---
title: "get_possible_conversions メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ソース文書に対する可能な変換を取得します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

ソース文書に対する可能な変換を取得します。

返されたオブジェクトは、主要および二次フォーマットを含むすべての変換オプションへのアクセスを提供し、ソースファイルに関するメタデータも含みます。

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### 例

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### 関連項目
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
