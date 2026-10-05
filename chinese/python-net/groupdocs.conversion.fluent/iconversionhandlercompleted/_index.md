---
title: "IConversionHandlerCompleted 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在设置 OnConversionFailed 后表示流式接口，允许设置 OnConversionCompleted 或继续进行 Convert/Compress。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/
is_root: false
weight: 230
---


## IConversionHandlerCompleted class

表示在设置了 `OnConversionFailed` 后的流式接口，允许设置 `OnConversionCompleted` 或继续执行 `Convert`/`Compress`。

IConversionHandlerCompleted 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/#options) | 压缩转换结果并返回一个继续操作，以继续执行 `Convert`。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/) | 执行转换链。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/#on_completed) | 注册一个回调函数，在文档转换成功完成时调用。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/#on_failed) | 注册一个回调函数，在文档转换失败时调用。重新注册会替换之前设置的处理程序。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed_action/) |  |

### 另见
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
