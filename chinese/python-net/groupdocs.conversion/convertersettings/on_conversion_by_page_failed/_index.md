---
title: "on_conversion_by_page_failed 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "当按页转换失败时调用的事件处理程序。"
type: docs
url: /zh/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

当按页转换失败时调用的事件处理程序。

为向后兼容保留：该值在 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 构造时合并到内部事件袋中（映射到 [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)），如果在 `events` 构造函数参数中也设置了相同的处理程序，则会被覆盖。

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### 另见
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
