---
title: "restore_schema 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性决定当 XML 架构缺失或无法加载时，转换是否允许解析 GML 文件中的属性。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/gmlloadoptions/restore_schema/
is_root: false
weight: 2030
---


## restore_schema property

该属性决定当 XML 架构缺失或无法加载时，转换是否允许解析 GML 文件中的属性。

如果设置为 True，转换读取器不需要 XML 架构的存在。默认值为 False。

### Definition:
```python
@property
def restore_schema(self):
    ...
@restore_schema.setter
def restore_schema(self, value):
    ...
```

### 另见
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
