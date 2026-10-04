---
title: "FontFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет документы шрифтов. Включает следующие типы Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Узнайте больше о форматах шрифтов здесьhttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /ru/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Определяет документы шрифтов. Включает следующие типы: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Узнайте больше о форматах шрифтов [здесь](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FontFileType](fontfiletype)() | Конструктор сериализации |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Файл с расширением .cff — это Compact Font Format, также известный как PostScript Type 1 или CIDFont. CFF служит контейнером для хранения нескольких шрифтов вместе в единой единице, известной как FontSet. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Файл с расширением .eot — это шрифт OpenType, встроенный в документ. Такие файлы в основном используются в веб‑файлах, например на веб‑странице. Он был создан Microsoft и поддерживается продуктами Microsoft, включая презентацию PowerPoint в формате .pps. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Файл с расширением .otf относится к формату шрифтов OpenType. Формат шрифтов OTF более масштабируем и расширяет существующие возможности форматов TTF для цифровой типографии. Разработанный Microsoft и Adobe, OTF сочетает возможности форматов PostScript и TrueType. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Файл с расширением .ttf представляет собой шрифтовые файлы, основанные на технологии шрифтов TrueType. Изначально он был разработан и выпущен компанией Apple Computer, Inc для Mac OS, а позже принят Microsoft для Windows OS. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Шрифты Type 1 — устаревшая технология Adobe, которая широко использовалась в настольных издательских программах и принтерах, поддерживающих PostScript. Хотя шрифты Type 1 не поддерживаются во многих современных платформах, веб‑браузерах и мобильных операционных системах, они всё ещё поддерживаются в некоторых операционных системах. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). Он представляет собой специфичный для формата сжатый контейнер, основанный либо на TrueType (.TTF), либо на OpenType (.OTT) типах шрифтов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). Он представляет собой специфичный для формата сжатый контейнер, основанный либо на TrueType (.TTF), либо на OpenType (.OTT) типах шрифтов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/font/woff/). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
