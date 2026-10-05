---
title: "IConversionByPageHandlerCompleted 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在页面转换设置了 OnConversionFailed 之后提供流式接口。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/
is_root: false
weight: 30
---


## IConversionByPageHandlerCompleted class

在为页面转换设置了 `OnConversionFailed` 后提供流式接口。允许设置 `OnConversionCompleted` 或继续执行 `Convert`/`Compress`。

IConversionByPageHandlerCompleted 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/compress/#options) | 压缩转换结果。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/convert/) | 执行转换链。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed/#on_completed) | 注册一个回调函数，在页面转换成功完成时调用。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/#on_failed) | 注册一个回调，以在页面转换失败时调用。重新调用将替换任何先前设置的处理程序。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed_action/) |  |

### 另见
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
