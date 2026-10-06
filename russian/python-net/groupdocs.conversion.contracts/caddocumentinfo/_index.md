---
title: "Класс CadDocumentInfo"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Содержит метаданные документа Cad."
type: docs
url: /ru/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Содержит метаданные документа Cad.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Без явного указания [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) эти листы представляют модельное пространство, которое всегда можно построить и поэтому всегда является листом, плюс каждый лист в пространстве бумаги, у которого сохранённые настройки страницы имеют положительные ширину и высоту, ограниченные [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Явные имена макетов выигрывают напрямую: листы тогда становятся предоставленными именами, которые содержит чертёж, сопоставленными по порядку, без фильтрации ни областью, ни настройками страницы.

Для DWF публикуемый набор страниц сообщается. Счёт, меньший единицы, равен нулю и сообщается, когда запрошенный диапазон не совпадает ни с одним листом чертежа, который его предоставляет: метаданные всё равно описывают чертёж, а ноль означает, что диапазон ничего не выбирает, а не приводит к ошибке вызывающего, который спросил, что содержит чертёж. Конверсия с теми же параметрами загрузки действительно завершается с ошибкой.

Следовательно, счёт не является размером [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), который перечисляет все конфигурации печати, содержащиеся в чертеже, включая те, из которых нельзя опубликовать лист, и не предсказывает, сколько страниц будет выдано при конкретной конверсии.

Тип CadDocumentInfo раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | Дата создания документа. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Формат документа. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | Высота CAD‑документа. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Слои в документе. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Макеты в документе. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Количество страниц документа. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | Перечисление всех свойств, которые можно получить для текущей информации о документе. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | Размер документа в байтах. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | Ширина CAD‑документа. |

### См. также
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
