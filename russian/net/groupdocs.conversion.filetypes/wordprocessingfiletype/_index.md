---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет файлы обработки текста, содержащие пользовательскую информацию в формате простого текста или форматированного текста. Формат простого текста содержит неформатированный текст и не позволяет применять шрифты, настройки страниц и т.д. В отличие от этого, формат форматированного текста позволяет использовать параметры форматирования, такие как установка шрифтов, типы, стили, полужирный, курсив, подчёркивание и т.д., поля страниц, заголовки, маркеры и нумерацию, а также несколько других функций форматирования. Включает следующие типы файлов Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Узнайте больше о форматах обработки текста здесьhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /ru/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Определяет файлы обработки текста, которые содержат пользовательскую информацию в формате простого текста или форматированного текста. Формат простого текста содержит неформатированный текст и не может применять шрифты или настройки страницы и т.д. В отличие от этого, формат форматированного текста позволяет параметры форматирования, такие как установка типа шрифтов, стили (жирный, курсив, подчёркнутый и т.д.), поля страницы, заголовки, маркеры и нумерацию, а также несколько других функций форматирования. Включает следующие типы файлов: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Узнайте больше о форматах обработки текста [здесь](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Файлы с расширением .doc представляют документы, созданные Microsoft Word или другими программами обработки текста в бинарном формате. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Файлы DOCM — это документы Microsoft Word 2007 и новее с возможностью выполнения макросов. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX — известный формат документов Microsoft Word. Появился в 2007 году с выпуском Microsoft Office 2007; структура этого нового формата документа была изменена с простого бинарного на комбинацию XML и бинарных файлов. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Файлы с расширением .DOT являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно отформатированные настройки для создания последующих файлов DOC или DOCX. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Файл с расширением DOTM представляет шаблонный файл, созданный в Microsoft Word 2007 и новее. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Файлы с расширением DOTX являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно отформатированные настройки для создания последующих файлов DOCX. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word — это Office Open XML WordprocessingML, хранящийся в плоском XML‑файле вместо ZIP‑пакета. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Текстовые файлы, созданные с использованием диалектов языка Markdown, сохраняются с расширением .MD или .MARKDOWN. Файлы MD сохраняются в формате простого текста, использующего язык Markdown, который также включает встроенные текстовые символы, определяющие, как можно форматировать текст, такие как отступы, таблицы, шрифты и заголовки. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Файлы ODT — это тип документов, созданных приложениями обработки текста, основанными на формате OpenDocument Text. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Файлы с расширением OTT представляют шаблонные документы, генерируемые приложениями в соответствии со стандартом OpenDocument от OASIS. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Введённый и документированный Microsoft, Rich Text Format (RTF) представляет метод кодирования отформатированного текста и графики для использования в приложениях. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Файл с расширением .TXT представляет текстовый документ, содержащий простой текст в виде строк. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/txt). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
