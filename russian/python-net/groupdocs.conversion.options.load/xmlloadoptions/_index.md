---
title: "Класс XmlLoadOptions"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Параметры загрузки документов XML."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

Параметры загрузки документов XML.

Тип XmlLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | Создаёт новый экземпляр [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/). |

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
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | Пользовательский CSS‑стиль, применяемый к документу во время конвертации. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | Тип файла входного документа. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | Настройки полей страницы. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | Настройки ориентации страницы. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | Масштабирование макета страницы, применяемое при загрузке документа. По умолчанию: None. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | Флаг генерации нумерации страниц для конвертированного документа (по умолчанию: False). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | Настройки размера страницы. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | Свойство указывает, загружаются ли внешние ресурсы. |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | XML‑документ используется в качестве источника данных. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | Внешние ресурсы, которые всегда будут загружаться. |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | Поток XSL-FO документа для конвертации XML с использованием файла разметки XSL-FO. |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | Поток XSLT документа для конвертации XML с выполнением XSL‑трансформации в HTML. |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | Базовый путь/url для html. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | Действие, используемое для настройки заголовков запроса, где первым параметром является Uri. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Провайдер учётных данных для Uri. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | Кодировка, используемая при загрузке веб‑документа. Если установлено None, кодировка будет определена из атрибута набора символов документа. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | Режим рендеринга HTML управляет тем, как отображается HTML‑контент. По умолчанию: AbsolutePositioning. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | Тайм‑аут для загрузки внешних ресурсов. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | Свойство указывает, использовать ли PDF для конвертации (по умолчанию: False). (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | Уровень масштабирования в процентах, применяемый к тегу `<body>` документа перед конвертацией, изменяющий визуальное отображение документа. (унаследовано от [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |

### См. также
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
