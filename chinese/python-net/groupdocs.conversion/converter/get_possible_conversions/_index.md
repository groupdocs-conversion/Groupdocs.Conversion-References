---
title: "get_possible_conversions 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "检索源文档的可能转换。"
type: docs
url: /zh/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

检索源文档的可能转换。

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### 示例

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### 另见
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
