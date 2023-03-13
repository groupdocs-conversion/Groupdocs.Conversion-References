---
title: FontFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет документы шрифтов Включает следующие типы Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Подробнее о форматах шрифтовздесьhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /ru/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Определяет документы шрифтов Включает следующие типы: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Подробнее о форматах шрифтов[здесь](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FontFileType](fontfiletype)() | Конструктор сериализации |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит хеш-функцией по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Файл с расширением .cff представляет собой компактный формат шрифта и также известен как PostScript Type 1 или CIDFont. CFF действует как контейнер для хранения нескольких шрифтов вместе в одном блоке, известном как FontSet. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Файл с расширением .eot — это шрифт OpenType, встроенный в документ. Они в основном используются в веб-файлах, таких как веб-страницы. Он был создан корпорацией Майкрософт и поддерживается продуктами Майкрософт, включая файл презентации PowerPoint в формате .pps. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Файл с расширением .otf относится к формату шрифта OpenType. Формат шрифта OTF является более масштабируемым и расширяет существующие возможности форматов TTF для цифровой типографики. Разработанный Microsoft и Adobe, OTF сочетает в себе функции форматов шрифтов PostScript и TrueType. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Файл с расширением .ttf представляет собой файлы шрифтов, основанные на технологии шрифтов спецификаций TrueType. Первоначально он был разработан и запущен Apple Computer, Inc для Mac OS, а затем был адаптирован Microsoft для ОС Windows. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Шрифты Type 1 — это устаревшая технология Adobe, которая широко использовалась в настольных издательских программах и принтерах, которые могли использовать PostScript. Хотя шрифты Type 1 не поддерживаются на многих современных платформах, веб-браузерах и мобильных операционных системах, они по-прежнему поддерживаются в некоторых операционных системах. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Файл с расширением .woff представляет собой файл веб-шрифта, основанный на формате веб-открытых шрифтов (WOFF). Он имеет сжатый контейнер для конкретного формата на основе типов шрифтов TrueType (.TTF) или OpenType (.OTT). Подробнее об этом формате файла[здесь](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Файл с расширением .woff представляет собой файл веб-шрифта, основанный на формате веб-открытых шрифтов (WOFF). Он имеет сжатый контейнер для конкретного формата на основе типов шрифтов TrueType (.TTF) или OpenType (.OTT). Подробнее об этом формате файла[здесь](https://docs.fileformat.com/font/woff/) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
