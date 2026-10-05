---
title: "get_all_possible_conversions 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "获取所有支持的转换。"
type: docs
url: /zh/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

获取所有支持的转换。

了解更多关于支持的转换：
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### 示例

```python
from groupdocs.conversion import Converter

# 检索所有可能的转换
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### 另见
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
