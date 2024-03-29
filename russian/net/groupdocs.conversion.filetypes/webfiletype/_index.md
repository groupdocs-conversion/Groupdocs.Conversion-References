---
title: WebFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет вебдокументы. Включает следующие типы файлов Xml./webfiletype/xmlJson./webfiletype/jsonHtml./webfiletype/htmlHtm./webfiletype/htmMht./webfiletype/mhtMhtml./webfiletype/mhtmlChm./webfiletype/chm
type: docs
weight: 1080
url: /ru/net/groupdocs.conversion.filetypes/webfiletype/
---
## WebFileType class

Определяет веб-документы. Включает следующие типы файлов: [`Xml`](./xml)[`Json`](./json)[`Html`](./html)[`Htm`](./htm)[`Mht`](./mht)[`Mhtml`](./mhtml)[`Chm`](./chm)

```csharp
public sealed class WebFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WebFileType](webfiletype)() | Конструктор сериализации |

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
| [explicit operator](../../groupdocs.conversion.filetypes/webfiletype/op_explicit) | Явное преобразование DataFileType в WebFileType |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Chm](../../groupdocs.conversion.filetypes/webfiletype/chm) | Формат файла CHM представляет файл справки Microsoft HTML, который состоит из набора HTML-страниц. Он предоставляет указатель для быстрого доступа к разделам и навигации по различным частям справочного документа. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/web/chm) . |
| static readonly [Htm](../../groupdocs.conversion.filetypes/webfiletype/htm) | HTM (Hyper Text Markup Language) — это расширение для веб-страниц, созданных для отображения в браузерах. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/web/html) . |
| static readonly [Html](../../groupdocs.conversion.filetypes/webfiletype/html) | HTML (Hyper Text Markup Language) — это расширение для веб-страниц, созданных для отображения в браузерах. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.conversion.filetypes/webfiletype/json) | JSON (JavaScript Object Notation) — это открытый стандартный формат файла для обмена данными, который использует удобочитаемый текст для хранения и передачи данных. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/web/json) . |
| static readonly [Mht](../../groupdocs.conversion.filetypes/webfiletype/mht) | Файлы с расширением MHTML представляют формат архива веб-страницы, который может быть создан рядом различных приложений. Этот формат известен как формат архива, поскольку он сохраняет веб-код HTML и связанные ресурсы в одном файле. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/web/mhtml) . |
| static readonly [Mhtml](../../groupdocs.conversion.filetypes/webfiletype/mhtml) | Файлы с расширением MHTML представляют формат архива веб-страницы, который может быть создан рядом различных приложений. Этот формат известен как формат архива, поскольку он сохраняет веб-код HTML и связанные ресурсы в одном файле. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/web/mhtml) . |
| static readonly [Xml](../../groupdocs.conversion.filetypes/webfiletype/xml) | XML означает расширяемый язык разметки, похожий на HTML, но отличающийся использованием тегов для определения объектов. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/web/xml) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
