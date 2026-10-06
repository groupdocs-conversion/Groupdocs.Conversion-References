---
title: "MarkdownOptions класс"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Представляет параметры конвертации в тип файла markdown."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/markdownoptions/
is_root: false
weight: 290
---


## MarkdownOptions class

Представляет параметры конвертации в тип файла markdown.

Тип MarkdownOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/__init__/) | Инициализирует новый экземпляр [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/) класса. |

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
| [export_images_as_base64](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) | Опция export_images_as_base64 определяет, экспортируются ли изображения в формате base64. |
| [image_saving_callback](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/) | Обратный вызов, вызываемый один раз для каждого изображения при сохранении Markdown. Позволяет вызывающему сохранять изображения внешне и заменять URI, встроенный в документ. Имеет приоритет над [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/), если он не None. |

### См. также
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
