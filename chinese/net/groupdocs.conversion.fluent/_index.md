---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "该命名空间提供用于流式转换的接口。"
type: docs
weight: 60
url: /zh/net/groupdocs.conversion.fluent/
---
该命名空间提供用于流式转换的接口。

## 接口

| 接口 | 描述 |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | 处理转换页面完成 |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | 处理转换完成或执行转换 |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | 仅设置按页转换处理程序的流畅接口。处理程序通过[`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage)注册。 |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | 扁平化的按页转换处理程序阶段。每页对应的[`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage)镜像。 |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | 用于设置按页转换选项或处理程序配置的流畅接口。允许以任意顺序设置选项或处理程序，但每个只能设置一次，或两者都跳过。 |
| [IConversionCompleted](./iconversioncompleted) | 处理转换完成 |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | 处理转换完成或执行转换 |
| [IConversionCompressResult](./iconversioncompressresult) | 可以将所有转换结果压缩为单个归档文件 |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | `Compress(...)`之后的继续。继续使用`Convert`；通过[`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents)在入口阶段注册压缩流处理程序。 |
| [IConversionConvert](./iconversionconvert) | 执行转换 |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | 转换选项 |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | 转换选项或转换完成或执行 |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | 转换选项或转换完成或执行 |
| [IConversionConvertOptions](./iconversionconvertoptions) | 转换选项 |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | 压缩或转换 |
| [IConversionFrom](./iconversionfrom) | 设置转换源 |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | 获取源文档信息——页面计数以及特定文件类型的其他文档属性。 |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | 获取源文档的可能转换。 |
| [IConversionHandlerOnly](./iconversionhandleronly) | 仅设置转换处理程序的流畅接口。处理程序通过[`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage)注册。 |
| [IConversionHandlersStage](./iconversionhandlersstage) | 扁平化的转换处理程序阶段。允许以任意顺序和任意次数设置`OnConversionCompleted`或`OnConversionFailed`，然后再进行`Convert`/`Compress`。事件应通过[`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents)在早期阶段注册，而不是在此阶段。 |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | 检查源文档是否受密码保护 |
| [IConversionLoadOptions](./iconversionloadoptions) | 转换加载选项 |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | 转换加载选项或已加载文档的操作 |
| [IConversionOptionsOnly](./iconversionoptionsonly) | 仅设置转换选项的流畅接口。 |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | 转换选项或转换处理程序设置。 |
| [IConversionSettings](./iconversionsettings) | 在入口阶段（`Load`之前）设置转换设置或事件。 |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | 转换设置或转换源 |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | 提供已加载文档的可能操作 |
| [IConversionTo](./iconversionto) | 设置转换后文档的存储方式 |

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
