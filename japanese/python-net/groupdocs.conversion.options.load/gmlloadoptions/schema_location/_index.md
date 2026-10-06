---
title: "schema_location プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "schemalocation はスペースで区切られた URI ペアのリストで、各ペアの最初の URI が名前空間 URI、2 番目の URI がその名前空間の XML スキーマへのパスです。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

schema_location はスペースで区切られた URI ペアのリストで、各ペアの最初の URI が名前空間 URI、2 番目の URI がその名前空間の XML スキーマへのパスです。

None に設定すると、Conversion はドキュメントのルート要素から schemaLocation 属性を読み取ろうとします。デフォルト値は None です。

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### 関連項目
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
