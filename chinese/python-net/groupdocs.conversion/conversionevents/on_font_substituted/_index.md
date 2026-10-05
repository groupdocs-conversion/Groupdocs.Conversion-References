---
title: "on_font_substituted 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "当源文档引用的字体不可用且被替换时触发的事件（可以是由客户提供的 FontSubstitute 规则、配置的默认字体，或由…）"
type: docs
url: /zh/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

当源文档引用的字体不可用且被替换时触发的事件（替换方式可以是客户提供的[`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/)规则、配置的默认字体，或转换管道的内部回退）。

该事件在单次 `Converter.Convert(...)` 调用中会根据 `(SourceFileName, OriginalFontName)` 进行去重——订阅者每个缺失字体在每个源文档中最多收到一次通知。事件在转换线程上同步触发。图像转换不会触发此事件。

对于演示文稿文档，字体替换仅在 Windows 上检测到，因为引擎通过平台特定的字体匹配来解析，而该功能在其他操作系统上不可用。

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### 另见
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
