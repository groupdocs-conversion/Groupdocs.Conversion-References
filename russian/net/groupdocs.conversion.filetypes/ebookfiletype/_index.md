---
title: "EBookFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет документы EBook. Включает следующие типы файлов Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3"
type: docs
weight: 1110
url: /ru/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

Определяет документы EBook. Включает следующие типы файлов: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EBookFileType](ebookfiletype)() | Конструктор сериализации |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | AZW3, также известный как Kindle Format 8 (KF8), является модифицированной версией цифрового формата электронных книг AZW, разработанной для устройств Amazon Kindle. Этот формат улучшает старые файлы AZW и используется только на устройствах Kindle Fire, сохраняя обратную совместимость с предшествующими форматами, т.е. MOBI и AZW. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | Расширение EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и читателей. Этот формат стал настолько распространённым, что поддерживается многими электронными читалками и программными приложениями. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/ebook/epub). |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | Формат файлов MOBI — один из самых широко используемых форматов электронных книг. Этот формат улучшает старый формат OEB (Open Ebook Format) и использовался как проприетарный формат для Mobipocket Reader. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/ebook/mobi). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
