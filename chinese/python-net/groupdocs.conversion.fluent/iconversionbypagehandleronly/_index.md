---
title: "IConversionByPageHandlerOnly 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "仅提供设置按页转换处理程序的流式接口。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

仅提供设置按页转换处理程序的流式接口。

继承 [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) 用于 `Convert`/`Compress`；通过 `new` 关键字保留分阶段的 `OnConversion*` 重载，以保持向后兼容性。

IConversionByPageHandlerOnly 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | 压缩转换结果；通过 [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) 在入口阶段注册压缩流处理程序（设置 `OnCompressionCompleted`），而不是使用已废弃的流式链方法。 |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | 执行转换链。 |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | 注册一个回调函数，在页面转换成功完成时调用。 |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | 注册一个回调函数，在页面转换失败时调用。 |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### 另见
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
