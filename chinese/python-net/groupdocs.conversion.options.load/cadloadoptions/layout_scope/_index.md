---
title: "layout_scope 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "确定要转换的绘图空间的布局范围。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

确定要转换的绘图空间的布局范围。默认是[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)，它不限制转换。当提供[`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)时会被忽略，因为显式的布局名称始终优先。`None` 值将被视为[`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)。

如果范围未选择绘图提供的任何工作表，转换将因 `InvalidLoadOptionsException` 而失败，该异常会列出范围和可用的工作表，而不是渲染被排除的空间。完全不提供工作表的绘图不受影响，仍会作为单个单元进行转换。转换为 PDF/UA-1 时不予遵守，原因见 [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)。

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### 另见
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
