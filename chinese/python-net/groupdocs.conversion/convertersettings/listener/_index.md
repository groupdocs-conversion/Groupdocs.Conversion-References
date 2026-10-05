---
title: "listener 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "用于监控转换状态和进度的转换器监听器实现，其 Started、Progress 和 Completed 回调被转发到 ConversionEvents.onconversionstarted…"
type: docs
url: /zh/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

用于监控转换状态和进度的转换器监听器实现，其 Started、Progress 和 Completed 回调在 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 构造期间转发至 [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/)、[`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/)、以及 [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/)。

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### 另见
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
