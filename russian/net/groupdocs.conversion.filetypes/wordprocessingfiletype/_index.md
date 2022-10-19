---
title: WordProcessingFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет файлы обработки текста которые содержат информацию о пользователе в формате обычного текста или расширенного текста. Формат обычного текстового файла содержит неформатированный текст и к нему нельзя применить настройки шрифта страницы и т. д. Напротив формат файла расширенного текста позволяет параметры форматирования такие как установка типа шрифта стилей полужирный курсив подчеркивание и т. д. поля страницы заголовки маркеры и цифры а также некоторые другие функции форматирования. Включает следующие типы файлов Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log./wordprocessingfiletype/log . Подробнее о форматах обработки текстовздесьhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 960
url: /ru/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Определяет файлы обработки текста, которые содержат информацию о пользователе в формате обычного текста или расширенного текста. Формат обычного текстового файла содержит неформатированный текст, и к нему нельзя применить настройки шрифта, страницы и т. д. Напротив, формат файла расширенного текста позволяет параметры форматирования, такие как установка типа шрифта, стилей (полужирный, курсив, подчеркивание и т. д.), поля страницы, заголовки, маркеры и цифры, а также некоторые другие функции форматирования. Включает следующие типы файлов: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`Mobi`](./mobi) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . [`Log`](./log) . Подробнее о форматах обработки текстов[здесь](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Конструктор сериализации |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Файл family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит хеш-функцией по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | AZW3, также известный как Kindle Format 8 (KF8), представляет собой модифицированную версию формата цифровых файлов электронных книг AZW, разработанную для устройств Amazon Kindle. Этот формат представляет собой усовершенствование старых файлов AZW и используется на устройствах Kindle Fire только с обратной совместимостью для исходного формата файла, т. е. MOBI и AZW. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Файлы с расширением .doc представляют собой документы, сгенерированные Microsoft Word или другими текстовыми редакторами в двоичном формате. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Файлы DOCM представляют собой документы Microsoft Word 2007 или более поздней версии с возможностью запуска макросов. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX — широко известный формат документов Microsoft Word. Представленный в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого двоичного файла на комбинацию XML и двоичных файлов. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Файлы с расширением .DOT представляют собой файлы шаблонов, созданные Microsoft Word с предварительно отформатированными настройками для создания дополнительных файлов DOC или DOCX. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Файл с расширением DOTM представляет собой файл шаблона, созданный с помощью Microsoft Word 2007 или более поздней версии. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Файлы с расширением DOTX представляют собой файлы шаблонов, созданные Microsoft Word для предварительно отформатированных настроек для создания дополнительных файлов DOCX. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | Файл с расширением .LOG представляет собой текстовый документ, содержащий обычный текст в виде строк. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Текстовые файлы, созданные с использованием диалектов языка Markdown, сохраняются с расширением .MD или .MARKDOWN. Файлы MD сохраняются в текстовом формате с использованием языка Markdown, который также включает встроенные текстовые символы, определяющие способ форматирования текста, например отступы, форматирование таблиц, шрифты и заголовки. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | Формат файла MOBI является одним из наиболее широко используемых форматов файлов электронных книг. Этот формат является усовершенствованием старого формата OEB (Open Ebook Format) и использовался в качестве собственного формата для Mobipocket Reader. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Файлы ODT представляют собой тип документов, созданных с помощью приложений для обработки текстов, основанных на формате текстового файла OpenDocument. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Файлы с расширением OTT представляют собой шаблонные документы, созданные приложениями в соответствии со стандартным форматом OASIS OpenDocument. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Представленный и задокументированный Microsoft формат Rich Text Format (RTF) представляет собой метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | Файл с расширением .SQL представляет собой текстовый документ, содержащий sql. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Файл с расширением .TXT представляет собой текстовый документ, содержащий обычный текст в виде строк. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/txt) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
