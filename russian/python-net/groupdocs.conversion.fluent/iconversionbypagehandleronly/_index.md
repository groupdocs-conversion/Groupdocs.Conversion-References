---
title: "Класс IConversionByPageHandlerOnly"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Предоставляет плавный интерфейс для установки только обработчиков конвертации по страницам."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Предоставляет плавный интерфейс для установки только обработчиков конвертации по страницам.

Наследует [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) для `Convert`/`Compress`; перегруженные `OnConversion*` сохраняются с помощью ключевого слова `new` для поддержания обратной совместимости.

Тип IConversionByPageHandlerOnly раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Сжимает результаты конвертации; зарегистрируйте обработчик сжатого потока на начальном этапе через [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (устанавливая `OnCompressionCompleted`) вместо использования устаревшего метода цепочки fluent. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Выполняет цепочку конвертации. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Регистрирует обратный вызов, который будет выполнен при успешном завершении конвертации страницы. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Регистрирует обратный вызов, который будет выполнен при ошибке конвертации страницы. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### См. также
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
