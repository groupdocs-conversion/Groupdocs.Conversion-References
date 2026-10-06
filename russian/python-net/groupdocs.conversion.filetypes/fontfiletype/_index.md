---
title: "Класс FontFileType"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Представляет типы шрифтовых документов."
type: docs
url: /ru/python-net/groupdocs.conversion.filetypes/fontfiletype/
is_root: false
weight: 100
---


## FontFileType class

Представляет типы шрифтовых документов.

Включает следующие типы:
- [`FontFileType.ttf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf/)
- [`FontFileType.eot`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot/)
- [`FontFileType.otf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf/)
- [`FontFileType.cff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff/)
- [`FontFileType.type1`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1/)
- [`FontFileType.woff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff/)
- [`FontFileType.woff2`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2/)

Узнайте больше о форматах шрифтов https://docs.fileformat.com/font/.

Тип FontFileType раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/__init__/) | Инициализирует FontFileType для сериализации. |

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
| [TTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf/) | Файл с расширением .ttf представляет шрифтовые файлы, основанные на технологии шрифтов TrueType. Изначально он был разработан и выпущен компанией Apple Computer, Inc для Mac OS, а позже принят Microsoft для Windows OS. Узнайте больше об этом формате файла здесь. |
| [EOT](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot/) | Файл с расширением .eot — это шрифт OpenType, встроенный в документ. Такие шрифты в основном используются в веб‑файлах, например на веб‑странице. Он был создан Microsoft и поддерживается продуктами Microsoft, включая презентацию PowerPoint в формате .pps. Узнайте больше об этом формате файла здесь. |
| [OTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf/) | Файл с расширением .otf относится к формату шрифтов OpenType. Формат OTF более масштабируемый и расширяет существующие возможности форматов TTF для цифровой типографии. Разработанный Microsoft и Adobe, OTF сочетает в себе возможности форматов PostScript и TrueType. Узнайте больше об этом формате файла здесь. |
| [CFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff/) | Файл с расширением .cff — это Compact Font Format, также известный как PostScript Type 1 или CIDFont. CFF служит контейнером для хранения нескольких шрифтов вместе в единой единице, известной как FontSet. Узнайте больше об этом формате файла здесь. |
| [TYPE1](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1/) | Шрифты Type 1 — это устаревшая технология Adobe, широко использовавшаяся в настольных издательских программах и принтерах, поддерживающих PostScript. Хотя шрифты Type 1 не поддерживаются на многих современных платформах, веб‑браузерах и мобильных операционных системах, они всё ещё поддерживаются в некоторых операционных системах. Узнайте больше об этом формате файла здесь. |
| [WOFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff/) | Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). Он представляет собой форматно‑специфичный сжатый контейнер, основанный либо на шрифтах TrueType (.TTF), либо OpenType (.OTT). Узнайте больше об этом формате файла здесь. |
| [WOFF2](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2/) | Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). Он представляет собой форматно‑специфичный сжатый контейнер, основанный либо на шрифтах TrueType (.TTF), либо OpenType (.OTT). Узнайте больше об этом формате файла здесь. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Неизвестный тип файла (унаследовано от [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### См. также
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
