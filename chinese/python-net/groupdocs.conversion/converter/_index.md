---
title: "Converter 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示控制文档转换过程的主类。"
type: docs
url: /zh/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

表示控制文档转换过程的主类。

Converter 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | 初始化 Converter 的新实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | 初始化一个新的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | 初始化一个新的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | 使用显式转换事件初始化一个新的 Converter。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | 使用显式转换事件初始化一个新的 Converter 实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | 初始化一个新的 Converter 实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | 初始化一个新的 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | 初始化 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 类的新实例。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | 使用显式转换事件初始化一个新的 Converter。 |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | 使用显式转换事件初始化一个新的 Converter。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | 转换源文档并保存整个转换后的文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | 转换源文档并保存完整的转换后文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | 转换源文档并保存完整的转换后文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | 转换源文档并保存完整的转换后文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | 转换源文档并保存完整的转换后文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | 逐页转换源文档并保存转换后的文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | 逐页转换源文档并保存转换后的文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | 逐页转换源文档并保存转换后的文档。 |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | 逐页转换源文档并保存转换后的文档。 |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | 释放资源。 |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | 获取所有支持的转换。 |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | 检索源文档信息，包括页数和文件类型特定的其他属性。 |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | 检索源文档的可能转换。 |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | 获取提供的文档扩展名支持的转换。 |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | 检查源文档是否受密码保护。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
使用 `Converter` 的任务指南：

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### 另见
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
