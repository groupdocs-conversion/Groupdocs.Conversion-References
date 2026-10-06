---
title: "Класс EBookFileType"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Определяет документы EBook."
type: docs
url: /ru/python-net/groupdocs.conversion.filetypes/ebookfiletype/
is_root: false
weight: 60
---


## EBookFileType class

Определяет документы EBook. Включает следующие типы файлов: [`EBookFileType.epub`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/epub/), [`EBookFileType.mobi`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/mobi/), [`EBookFileType.azw3`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/azw3/).

Тип EBookFileType раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/__init__/) | Инициализирует новый [`EBookFileType`](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/) экземпляр для сериализации. |

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
| [EPUB](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/epub/) | Расширение EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и читателей. Формат стал настолько распространённым, что поддерживается многими электронными читалками и программными приложениями. Узнайте больше об этом формате файла здесь. |
| [MOBI](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/mobi/) | Формат файла MOBI — один из самых широко используемых форматов электронных книг. Формат является улучшением старого формата OEB (Open Ebook Format) и использовался как проприетарный формат для Mobipocket Reader. Узнайте больше об этом формате файла здесь. |
| [AZW3](/conversion/python-net/groupdocs.conversion.filetypes/ebookfiletype/azw3/) | AZW3, также известный как Kindle Format 8 (KF8), — модифицированная версия цифрового формата файлов AZW, разработанная для устройств Amazon Kindle. Формат представляет собой улучшение более старых файлов AZW и используется только на устройствах Kindle Fire с обратной совместимостью с предшествующим форматом, то есть MOBI и AZW. Узнайте больше об этом формате файла здесь. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Неизвестный тип файла (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### См. также
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
