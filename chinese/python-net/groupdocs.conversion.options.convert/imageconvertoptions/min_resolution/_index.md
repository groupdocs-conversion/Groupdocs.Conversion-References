---
title: "min_resolution 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "当启用 ImageConvertOptions.CapResolutionToPageContent 时，对受限渲染 DPI 应用的每轴下限。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/
is_root: false
weight: 2130
---


## min_resolution property

在启用 [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) 时，应用于受限渲染 DPI 的每轴下限。

受限 DPI 永不低于此值。默认值为 0（无下限）。

### Definition:
```python
@property
def min_resolution(self):
    ...
@min_resolution.setter
def min_resolution(self, value):
    ...
```

### 另见
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
