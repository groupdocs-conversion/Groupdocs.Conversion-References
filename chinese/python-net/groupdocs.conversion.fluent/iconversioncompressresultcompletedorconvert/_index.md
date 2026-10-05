---
title: "IConversionCompressResultCompletedOrConvert 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "Compress(...) 之后的继续操作。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/
is_root: false
weight: 130
---


## IConversionCompressResultCompletedOrConvert class

在 `Compress(...)` 之后继续。直接使用 `Convert`；继承的 [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) 已过时 — 请改为在入口阶段通过 [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) 注册处理程序。

IConversionCompressResultCompletedOrConvert 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/convert/) | 执行转换链。 |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/#compressed_document_stream) | 接收压缩后的文档流。仅在设置了 `Compress(CompressionConvertOptions)` 时触发。 |
| [on_compression_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed_action/) |  |

### 另见
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
