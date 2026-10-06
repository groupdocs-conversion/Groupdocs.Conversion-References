---
title: "Класс IConversionHandlersStage"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Представляет упрощённый этап обработчиков конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Представляет упрощённый этап обработчиков конвертации.

Позволяет задавать `OnConversionCompleted` или `OnConversionFailed` в любом порядке и любое количество раз, перед переходом к `Convert` / `Compress`. События следует регистрировать на раннем этапе через [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) вместо этого этапа.

Тип IConversionHandlersStage раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Сжимает результаты конвертации. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Выполняет цепочку конвертации. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Регистрирует обратный вызов, который будет выполнен при успешном завершении конвертации документа, заменяя любой ранее установленный обработчик при повторном вызове. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Регистрирует обратный вызов, который будет выполнен при ошибке конвертации документа. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### См. также
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
