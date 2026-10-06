---
title: "Класс TxtLoadOptions"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Параметры загрузки документов Txt."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Параметры загрузки документов Txt.

Конфигурация шрифта для обычного текста:

Поскольку файлы TXT не содержат информацию о шрифте, используйте DefaultTextFont для указания шрифта при рендеринге содержимого обычного текста во время конвертации.

Тип TxtLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Инициализирует новый экземпляр [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Определяет, равны ли два экземпляра объекта. (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Служит функцией хеширования по умолчанию. (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Шрифт, используемый при рендеринге содержимого обычного текста во время конвертации. По умолчанию: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | Свойство определяет, как распознаются нумерованные элементы списка при конвертации обычного текстового документа. Значение по умолчанию: True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Кодировка, используемая при загрузке документа Txt. Может быть None. По умолчанию: None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Тип файла входного документа. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | Предпочтительный вариант обработки начальных пробелов. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Настройки полей, как определено в [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Параметры размера страницы для загрузки TXT‑документа. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | Предпочтительный параметр для обработки конечных пробелов. Значение по умолчанию — [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### См. также
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
