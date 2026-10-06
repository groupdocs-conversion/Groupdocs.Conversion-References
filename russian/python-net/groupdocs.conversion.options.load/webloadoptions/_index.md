---
title: "WebLoadOptions класс"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Предоставляет параметры для загрузки веб‑документов."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
weight: 550
---


## WebLoadOptions class

Предоставляет параметры для загрузки веб‑документов.

Тип WebLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/) | Создаёт новый экземпляр [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/). |

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
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | Базовый путь/URL для HTML. |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | Действие, используемое для настройки заголовков запросов, где первым параметром является Uri. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Поставщик учётных данных для Uri. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/custom_css_style/) | Свойство реализует [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | Кодировка, используемая при загрузке веб‑документа. Если установлено значение None, кодировка будет определена из атрибута набора символов документа. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format/) | Тип файла входного документа. |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | Режим рендеринга HTML контролирует, как отображается HTML‑контент. По умолчанию: AbsolutePositioning. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/margin_settings/) | Настройки полей. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/orientation_settings/) | Настройки ориентации. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_layout_options/) | Параметры макета страницы, используемые при загрузке веб‑документов. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering/) | Флаг, включающий или отключающий генерацию нумерации страниц в конвертируемом документе. По умолчанию: False. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | Тайм‑аут для загрузки внешних ресурсов. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/size_settings/) | Настройки размера. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources/) | Свойство реализует [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | Свойство указывает, следует ли использовать PDF для конвертации (по умолчанию: False). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources/) | Свойство разрешённых ресурсов реализует [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | Уровень масштабирования в процентах, применяемый к тегу `<body>` документа перед конвертацией, изменяющий визуальное отображение документа. |

### См. также
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
