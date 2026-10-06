---
title: "skip_external_resources プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このプロパティは外部リソースがロードされるかどうかを示します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/
is_root: false
weight: 2080
---


## skip_external_resources property

このプロパティは外部リソースがロードされるかどうかを示します。

True の場合、[`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) リストに含まれるものを除き、すべての外部リソースはロードされません。デフォルトは True です。

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### 関連項目
* class [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/)
