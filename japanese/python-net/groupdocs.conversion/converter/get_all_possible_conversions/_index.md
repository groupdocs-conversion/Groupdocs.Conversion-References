---
title: "get_all_possible_conversions メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "サポートされているすべての変換を取得します。"
type: docs
url: /ja/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

サポートされているすべての変換を取得します。

サポートされている変換についての詳細:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### 例

```python
from groupdocs.conversion import Converter

# 可能なすべての変換を取得する
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### 関連項目
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
