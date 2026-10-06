---
title: "Класс DatabaseFileType"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Определяет документы базы данных."
type: docs
url: /ru/python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 40
---


## DatabaseFileType class

Определяет документы баз данных. Включает следующие типы файлов.

- [`DatabaseFileType.nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/)
- [`DatabaseFileType.log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/)
- [`DatabaseFileType.sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/)

Тип DatabaseFileType раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/) | Инициализирует новый DatabaseFileType для сериализации. |

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
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/) | Файл с расширением .nsf (Notes Storage Facility) — это формат файлов базы данных, используемый программным обеспечением IBM Notes, ранее известным как Lotus Notes. Он определяет схему для хранения различных объектов, таких как электронные письма, встречи, документы, формы и представления. Узнайте больше об этом формате файла здесь. |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/) | Файл с расширением .log содержит список обычного текста с отметкой времени. Обычно детали определённой активности записываются программным обеспечением или операционными системами, чтобы помочь разработчикам или пользователям отслеживать, что происходило в определённый период времени. Узнайте больше об этом формате файла здесь. |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/) | Файл с расширением .sql — это файл Structured Query Language (SQL), содержащий код для работы с реляционными базами данных. Он используется для написания SQL‑запросов для операций CRUD (Create, Read, Update, Delete) над базами данных. Узнайте больше об этом формате файла здесь. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Неизвестный тип файла (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### См. также
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
