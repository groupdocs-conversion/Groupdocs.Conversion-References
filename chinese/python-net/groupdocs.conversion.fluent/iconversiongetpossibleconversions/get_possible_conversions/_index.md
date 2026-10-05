---
title: "get_possible_conversions 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "检索源文档的可能转换。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/get_possible_conversions/
is_root: false
weight: 1010
---


## get_possible_conversions

检索源文档的可能转换。

```python
def get_possible_conversions(self):
    ...
```

**Returns:** A `GroupDocs.Conversion.Fluent.PossibleConversions` object containing the source description and a collection of conversion options.

### 示例

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### 另见
* class [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/)
