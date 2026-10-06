---
title: "Класс ConversionEvents"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Агрегирует обработчики событий жизненного цикла конверсии."
type: docs
url: /ru/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Агрегирует обработчики событий жизненного цикла конверсии.

Передайте экземпляр в параметр `events` конструктора [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) или в fluent‑метод `WithEvents`.

Предпочтительно использовать это вместо отдельных свойств обработчика [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), которые устарели.

Тип ConversionEvents раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | Событие, которое вызывается, когда завершается сжатие выходных данных конвертации. Вызывается только в сборках, включающих конвейер сжатия (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Событие, которое срабатывает один раз, когда выполнение конвертации завершается, независимо от успеха или неудачи. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Прогресс конвертации в процентах (0–100), генерируется периодически. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Событие, которое вызывается один раз в начале выполнения конвертации, до обработки любого документа. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Событие вызывается один раз для каждой полной конвертации документа, завершившейся успешно. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Событие вызывается один раз для каждой полной конвертации документа, завершившейся с ошибкой. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Событие вызывается, когда шрифт, указанный в исходном документе, недоступен и заменяется (либо правилом [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) от клиента, либо настроенным шрифтом по умолчанию, либо внутренним резервным шрифтом конвертационного конвейера). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Событие вызывается один раз для каждой страницы, когда постраничная конвертация завершается успешно. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Событие вызывается один раз для каждой страницы, когда постраничная конвертация завершается с ошибкой. |

### См. также
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
