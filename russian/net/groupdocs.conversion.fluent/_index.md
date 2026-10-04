---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Пространство имён предоставляет интерфейсы для fluent‑конверсии."
type: docs
weight: 60
url: /ru/net/groupdocs.conversion.fluent/
---
Пространство имён предоставляет интерфейсы для fluent‑конверсии.

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Обработать завершение страницы конверсии |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Обработать завершение конвертации или выполнить конвертацию |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Гибкий интерфейс для установки только обработчиков конвертации по страницам. Обработчики регистрируются через [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Упрощённый этап обработчиков конвертации по страницам. По‑страничное отражение [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Гибкий интерфейс для установки параметров конвертации по страницам или настройки обработчиков. Позволяет задавать параметры или обработчики в любом порядке, но только один раз каждый, либо пропустить оба. |
| [IConversionCompleted](./iconversioncompleted) | Обработать завершение конвертации |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Обработать завершение конвертации или выполнить конвертацию |
| [IConversionCompressResult](./iconversioncompressresult) | Можно сжать все результаты конвертации в один архив |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Продолжение после `Compress(...)`. Перейти к `Convert`; зарегистрировать обработчик сжатого потока на этапе входа через [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Выполнить конвертацию |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Параметры конвертации |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Параметры конвертации или завершение конвертации или выполнить |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Параметры конвертации или завершение конвертации или выполнить |
| [IConversionConvertOptions](./iconversionconvertoptions) | Параметры конвертации |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Сжать или конвертировать |
| [IConversionFrom](./iconversionfrom) | Настроить источник для конвертации |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Получает информацию о исходном документе — количество страниц и другие свойства документа, специфичные для типа файла. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Получает возможные варианты конвертации для исходного документа. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Гибкий интерфейс для установки только обработчиков конвертации. Обработчики регистрируются через [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Упрощённый этап обработчиков конвертации. Позволяет задавать `OnConversionCompleted` или `OnConversionFailed` в любом порядке и любое количество раз, перед переходом к `Convert` / `Compress`. События следует регистрировать на раннем этапе через [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents), а не на этом этапе. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Проверяет, защищён ли исходный документ паролем |
| [IConversionLoadOptions](./iconversionloadoptions) | Опции загрузки конвертации |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Опции загрузки конвертации или действия с загруженным документом |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Гибкий интерфейс для установки только параметров конвертации. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Параметры конвертации или настройка обработчика конвертации. |
| [IConversionSettings](./iconversionsettings) | Настройте параметры конвертации или события на этапе входа (до `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Параметры конвертации или источник конвертации |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Предоставляет возможные действия с загруженным документом |
| [IConversionTo](./iconversionto) | Установите, как будет храниться конвертированный документ |

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
