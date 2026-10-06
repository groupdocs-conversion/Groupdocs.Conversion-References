---
title: "get_possible_conversions メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ソース文書に対する可能な変換を取得します。"
type: docs
url: /ja/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

ソース文書に対する可能な変換を取得します。

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### 例

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### 関連項目
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
