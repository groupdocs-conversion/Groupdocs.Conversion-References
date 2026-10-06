---
title: "Класс FinanceFileType"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Определяет типы финансовых документов."
type: docs
url: /ru/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Определяет типы финансовых документов.

Включает следующие типы: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Узнайте больше о финансовых форматах здесь: https://docs.fileformat.com/finance/.

Тип FinanceFileType раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Инициализирует FinanceFileType для сериализации. |

### Методы
| Метод | Описание |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Сравнивает текущий объект с другим. (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Реализует сравнение на равенство, определённое в [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Получает FileType для указанного расширения файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Возвращает FileType для указанного file_name. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Возвращает FileType для предоставленного потока документа. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Предоставляет функцию хеширования по умолчанию. (унаследовано от [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Строковое представление типа файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Описание типа файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Расширение файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Семейство файлов. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Формат файла. (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL — открытый международный стандарт цифровой бизнес-отчетности, широко используемый по всему миру. Это язык на основе XML, который использует элементы XBRL, известные как теги, для описания каждого элемента бизнес-данных с целью формирования данных для сортировки и анализа отчетов. Узнайте больше об этом файловом формате здесь. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | Внутри iXBRL содержимое XBRL обернуто в файловый формат xHTML, который использует XML‑теги. Как и XBRL, является корневым элементом файлов iXBRL. Формат XHTML представляет своё содержимое как набор различных типов документов и модулей. Все файлы в XHTML основаны на файловом формате XML и соответствуют стандартам XML‑документов. Узнайте больше об этом файловом формате здесь. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) — потоковый формат данных для обмена финансовой информацией, который возник из форматов Microsoft Open Financial Connectivity (OFC) и Intuit Open Exchange. Узнайте больше об этом файловом формате здесь. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Неизвестный тип файла (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### См. также
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
