---
title: "groupdocs.conversion.fluent"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "groupdocs.conversion.fluent 下的类型。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


`groupdocs.conversion.fluent` 下的类型。

### 类
| 类 | 描述 |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | 处理转换页面完成。 |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | 处理转换完成或执行转换。 |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | 在为页面转换设置了 `OnConversionFailed` 后提供流式接口。允许设置 `OnConversionCompleted` 或继续执行 `Convert`/`Compress`。 |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | 表示在为页面转换设置了 `OnConversionCompleted` 后的流式接口，允许配置 `OnConversionFailed` 或继续执行 `Convert`/`Compress`。 |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | 仅提供设置按页转换处理程序的流式接口。 |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | 提供设置页面转换处理程序的流式接口。 |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | 表示已展平的按页转换处理程序阶段。 |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | 用于设置按页转换选项或处理程序的流式接口。 |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | 处理转换完成。 |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | 处理转换完成或执行转换。 |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | 将所有转换结果压缩为单个归档文件。 |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | 处理压缩完成。 |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | 在 `Compress(...)` 之后继续。直接使用 `Convert`；继承的 [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) 已过时 — 请改为在入口阶段通过 [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) 注册处理程序。 |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | 执行转换。 |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | 表示转换的转换选项。 |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | 表示转换选项、完成处理或转换的执行。 |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | 表示转换选项、完成处理或执行。 |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | 表示转换的转换选项。 |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | 压缩或转换。 |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | 设置转换的源。 |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | 检索源文档信息，包括页数以及文件类型特有的其他属性。 |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | 获取源文档的可能转换。 |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | 表示在设置了 `OnConversionFailed` 后的流式接口，允许设置 `OnConversionCompleted` 或继续执行 `Convert`/`Compress`。 |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | 在设置了 `OnConversionCompleted` 后提供流式接口，允许配置 `OnConversionFailed` 或继续执行 `Convert`/`Compress`。 |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | 仅提供设置转换处理程序的流式接口。 |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | 提供设置转换处理程序的流式接口。允许以任意顺序设置 `OnConversionCompleted` 和/或 `OnConversionFailed`，每个最多一次，或两者皆不设置。 |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | 表示已展平的转换处理程序阶段。 |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | 检查源文档是否受密码保护。 |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | 表示转换加载选项。 |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | 表示已加载文档的转换加载选项或操作。 |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | 提供仅设置转换选项的流畅接口。 |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | 表示转换选项或转换处理程序设置。 |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | 在入口阶段（`Load` 之前）设置转换设置或事件。 |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | 表示转换设置或转换来源。 |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | 提供已加载文档的可能操作。 |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | 设置转换后文档的存储方式。 |
