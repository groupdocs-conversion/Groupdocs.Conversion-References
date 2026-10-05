---
title: "skip_external_resources 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性指示是否加载外部资源。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/
is_root: false
weight: 2170
---


## skip_external_resources property

属性指示是否加载外部资源。如果为 True，除 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) 列表中的资源外，所有外部资源都不会被加载。默认值：True。

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### 另见
* class [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/)
