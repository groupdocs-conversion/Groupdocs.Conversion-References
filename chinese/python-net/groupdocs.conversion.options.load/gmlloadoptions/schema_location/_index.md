---
title: "schema_location 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "schemalocation 是以空格分隔的 URI 对列表，每对中的第一个 URI 是命名空间 URI，第二个 URI 是该命名空间的 XML 架构路径。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

schema_location 是以空格分隔的 URI 对列表，每对中的第一个 URI 为命名空间 URI，第二个 URI 为该命名空间的 XML 架构路径。

如果设置为 None，Conversion 将尝试从文档根元素读取 schemaLocation 属性。默认值为 None。

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### 另见
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
