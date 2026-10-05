---
title: "IConversionHandlersStage 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示已展平的转换处理程序阶段。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

表示已展平的转换处理程序阶段。

允许以任意顺序和任意次数设置 `OnConversionCompleted` 或 `OnConversionFailed`，然后再继续 `Convert` / `Compress`。事件应在早期阶段通过 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) 注册，而不是在此阶段注册。

IConversionHandlersStage 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | 压缩转换结果。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | 执行转换链。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | 注册一个回调，在文档转换成功完成时调用，在重新调用时替换任何先前设置的处理程序。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | 注册一个回调函数，在文档转换失败时调用。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### 另见
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
