---
title: "Класс FontTransformation"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Описывает конфигурацию преобразования шрифта, включая атрибуты шрифта, применяемую после загрузки документа и замены шрифта."
type: docs
url: /ru/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Описывает конфигурацию преобразования шрифта, включая атрибуты шрифта, применяемую после загрузки документа и замены шрифта.

Тип FontTransformation содержит следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Создаёт преобразование шрифта с точным совпадением шрифта (размер и стиль должны совпадать). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Создаёт преобразование шрифта только по имени, совпадая с любым размером и стилем, при этом заменяющий шрифт сохраняет размер и стиль оригинального шрифта. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Создаёт преобразование шрифта с гибкими параметрами совпадения. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Определяет, равны ли два экземпляра объекта. (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Служит функцией хеширования по умолчанию. (наследовано от [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | Свойство указывает, совпадает ли любой размер шрифта для оригинального названия шрифта (true) или совпадает только точный размер шрифта, указанный в `OriginalFont` (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | Свойство определяет, совпадает ли любой стиль шрифта (жирный, курсив, подчёркнутый) оригинального шрифта (True) или требуется точный стиль шрифта, указанный в `OriginalFont` (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | Исходная спецификация шрифта для совпадения и замены. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | Спецификация заменяющего шрифта. |

### См. также
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
