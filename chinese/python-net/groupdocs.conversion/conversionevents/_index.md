---
title: "ConversionEvents 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "聚合转换生命周期事件处理程序。"
type: docs
url: /zh/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

聚合转换生命周期事件处理程序。

将实例传递给 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 构造函数的 `events` 参数或流式 `WithEvents` 方法。

建议使用此方式而非已过时的各个 [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) 处理程序属性。

ConversionEvents 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | 当转换输出的压缩完成时触发的事件。仅在包含压缩管道 (LIB_ZIP) 的构建中调用。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | 当转换运行完成时（无论成功或失败），触发一次的事件。 |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | 转换进度的百分比（0–100），定期触发。 |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | 在转换运行开始时（在处理任何文档之前）触发一次的事件。 |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | 每次成功完成的整体文档转换会触发一次的事件。 |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | 每次失败的整体文档转换会触发一次的事件。 |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | 当源文档引用的字体不可用且被替换时触发的事件（替换方式可以是客户提供的[`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/)规则、配置的默认字体，或转换管道的内部回退）。 |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | 每页的逐页转换成功完成时触发一次的事件。 |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | 每页的逐页转换失败时触发一次的事件。 |

### 另见
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
