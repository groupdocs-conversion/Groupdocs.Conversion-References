---
title: "ConsoleLogger 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "提供控制台日志记录器实现。"
type: docs
url: /zh/python-net/groupdocs.conversion.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

提供控制台日志记录器实现。

ConsoleLogger 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.logging/consolelogger/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [error](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error/#message-exception) | 写入错误日志消息。 |
| [error_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_file/) |  |
| [error_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_string/) |  |
| [trace](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace/#message) | 写入跟踪日志消息，提供有关应用程序流程的一般有用信息。 |
| [trace_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_file/) |  |
| [trace_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_string/) |  |
| [warning](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning/#message) | 写入警告日志消息。 |
| [warning_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_file/) |  |
| [warning_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_string/) |  |

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
* module [`groupdocs.conversion.logging`](/conversion/python-net/groupdocs.conversion.logging/)
