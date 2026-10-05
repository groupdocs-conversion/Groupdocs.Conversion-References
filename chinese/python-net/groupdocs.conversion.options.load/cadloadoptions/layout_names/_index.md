---
title: "layout_names 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "要转换的布局名称。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

要转换的布局名称。

转换为 PDF/UA-1 时不予遵守。该目标将图纸渲染为单个标记页面，无法为每个选定布局携带单独的工作表，因此整个图纸会被转换，而此处的设置不适用于它。

其他所有目标（包括 PDF）都会遵守选择。在这些目标上，名称会与图纸所包含的布局精确匹配，因此仅大小写不同的名称被视为不同的名称。与任何布局都不匹配的名称会被丢弃，只会导致调用者失去相应的工作表；如果列表中所有名称都未匹配，则会抛出 `InvalidLoadOptionsException`，其中列出未匹配的名称以及图纸实际包含的布局，而不是渲染调用者未请求的工作表。完全不包含任何布局的图纸则例外：因为没有可匹配的名称，所以不会拒绝任何内容。

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### 另见
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
