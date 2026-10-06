---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Типы в groupdocs.conversion.fluent."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Типы в `groupdocs.conversion.fluent`.

### Классы
| Класс | Описание |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Обрабатывает завершение страницы конвертации. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Обрабатывает завершение конвертации или выполняет конвертацию. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Предоставляет плавный интерфейс после установки `OnConversionFailed` для конвертации страниц. Позволяет установить `OnConversionCompleted` или перейти к `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Представляет плавный интерфейс после установки `OnConversionCompleted` для конвертации страниц, позволяя настроить `OnConversionFailed` или перейти к `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Предоставляет плавный интерфейс для установки только обработчиков конвертации по страницам. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Предоставляет плавный интерфейс для установки обработчиков конвертации страниц. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Представляет упрощённый этап обработчиков конвертации по страницам. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | Плавный интерфейс для установки параметров конвертации по страницам или настройки обработчиков. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Обрабатывает завершение конвертации. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Обрабатывайте завершение конвертации или выполните конвертацию. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Сжимает все результаты конвертации в один архив. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Обрабатывает завершение сжатия. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Продолжение после `Compress(...)`. Перейдите напрямую к `Convert`; унаследованный [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) устарел — вместо этого зарегистрируйте обработчик на этапе входа через [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/). |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Выполнить конвертацию. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Представляет параметры конвертации. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Представляет параметры конвертации, обработку завершения или выполнение конвертации. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Представляет параметры конвертации, обработку завершения или выполнение. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Представляет параметры конвертации. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Сжать или конвертировать. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Настраивает источник для конвертации. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Получает информацию о исходном документе, включая количество страниц и другие свойства, специфичные для типа файла. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Получает возможные варианты конвертации для исходного документа. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Представляет плавный интерфейс после установки `OnConversionFailed`, позволяя установить `OnConversionCompleted` или перейти к `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Предоставляет плавный интерфейс после установки `OnConversionCompleted`, позволяя настроить `OnConversionFailed` или перейти к `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Предоставляет плавный интерфейс для установки только обработчиков конвертации. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Предоставляет плавный интерфейс для установки обработчиков конвертации. Позволяет установить `OnConversionCompleted` и/или `OnConversionFailed` в любом порядке, не более одного раза каждый, либо пропустить оба. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Представляет упрощённый этап обработчиков конвертации. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Проверяет, защищён ли исходный документ паролем. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Представляет параметры загрузки конверсии. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Представляет параметры загрузки конверсии или действия с загруженным документом. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Предоставляет плавный интерфейс для установки только параметров конверсии. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Представляет параметры конверсии или настройку обработчика конверсии. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Настройте параметры конверсии или события на этапе входа (до `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Представляет настройки конверсии или источник конверсии. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Предоставляет возможные действия с загруженным документом. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Устанавливает, как сохраняется конвертированный документ. |
