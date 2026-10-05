---
title: "load_schemas_from_internet 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性决定转换是否允许从 Internet 加载 XML 架构。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/gmlloadoptions/load_schemas_from_internet/
is_root: false
weight: 2020
---


## load_schemas_from_internet property

该属性决定转换是否允许从 Internet 加载 XML 架构。

如果设置为 False，具有绝对 URI 且不以 'file://' 开头的架构将不会被加载。默认值为 False。

### Definition:
```python
@property
def load_schemas_from_internet(self):
    ...
@load_schemas_from_internet.setter
def load_schemas_from_internet(self, value):
    ...
```

### 另见
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
