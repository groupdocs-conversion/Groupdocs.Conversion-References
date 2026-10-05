---
title: "ConverterSettings 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "定义用于自定义 Converter 行为的设置。"
type: docs
url: /zh/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

定义用于自定义 Converter 行为的设置。

ConverterSettings 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | 使用默认值初始化 ConverterSettings 的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | 用于存储转换结果的缓存实现。 |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | 自定义字体目录路径。 |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | 用于监控转换状态和进度的转换器监听器实现，其 Started、Progress 和 Completed 回调在 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 构造期间转发至 [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/)、[`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/)、以及 [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/)。 |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | 用于记录转换过程的日志实现。 |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | 压缩完成的事件处理程序。 |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | 当按页转换失败时调用的事件处理程序。 |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | 当转换失败时调用的事件处理程序。 |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | 当设置为 True 时，转换器会递归扫描字体目录。 |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | 用于转换的临时文件夹。 |

### 示例

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 另见
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
