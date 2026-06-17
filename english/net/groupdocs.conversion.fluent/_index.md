---
title: GroupDocs.Conversion.Fluent
second_title: GroupDocs.Conversion for .NET API Reference
description: The namespace provides interfaces for fluent conversion.
type: docs
weight: 60
url: /net/groupdocs.conversion.fluent/
---
The namespace provides interfaces for fluent conversion.

## Interfaces

| Interface | Description |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Handle conversion page completed |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Handle conversion completed or execute conversion |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Fluent interface for setting only by-page conversion handlers. Inherits [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage) for `Convert`/`Compress`; the staged `OnConversion*` overloads are kept via the `new` keyword to preserve back-compat. |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Flattened by-page conversion handlers stage. Per-page mirror of [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Fluent interface for setting by-page conversion options or handler setup. Allows setting options or handlers in any order, but only once each, or skipping both. |
| [IConversionCompleted](./iconversioncompleted) | Handle conversion completed |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Handle conversion completed or execute conversion |
| [IConversionCompressResult](./iconversioncompressresult) | Can compress all conversion results in single archive |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Continuation after `Compress(...)`. Proceed directly with `Convert`; the inherited Stream}) is obsolete — register the handler at the entry stage via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) instead. |
| [IConversionConvert](./iconversionconvert) | Execute conversion |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Conversion convert options |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Conversion convert options or conversion completed or execute |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Conversion convert options or conversion completed or execute |
| [IConversionConvertOptions](./iconversionconvertoptions) | Conversion convert options |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Compress or convert |
| [IConversionFrom](./iconversionfrom) | Setup source for conversion |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Gets source document info - pages count and other document properties specific to the file type. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Gets possible conversions for the source document. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Fluent interface for setting only conversion handlers. Inherits [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage) for `Convert`/`Compress`; the staged `OnConversion*` overloads are kept via the `new` keyword to preserve the existing return types and back-compat. |
| [IConversionHandlersStage](./iconversionhandlersstage) | Flattened conversion handlers stage. Allows setting `OnConversionCompleted` or `OnConversionFailed` in any order and any number of times, before proceeding to `Convert` / `Compress`. Events should be registered at the early stage via [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) instead of in this stage. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Checks if source document is password protected |
| [IConversionLoadOptions](./iconversionloadoptions) | Conversion load options |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Conversion load options or actions with loaded document |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Fluent interface for setting only conversion options. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Conversion options or conversion handler setup. Exposes both the obsolete staged chain ([`IConversionHandlerOnly`](../groupdocs.conversion.fluent/iconversionhandleronly)) and the new flat [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionSettings](./iconversionsettings) | Setup conversion settings or events at the entry stage (before `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Conversion settings or conversion source |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Provides possible actions with loaded document |
| [IConversionTo](./iconversionto) | Set how converted document to be stored |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
