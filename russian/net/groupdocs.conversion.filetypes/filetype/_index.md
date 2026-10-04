---
title: "FileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Базовый класс типа файла"
type: docs
weight: 1130
url: /ru/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Базовый класс типа файла

```csharp
public class FileType : Enumeration
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileType](filetype)() | Конструктор сериализации |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Получает FileType для указанного fileExtension |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Возвращает FileType для указанного fileName |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Возвращает FileType для предоставленного document stream |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Возвращает все значения перечисления. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Неявное преобразование в строку |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Неизвестный тип файла |

### См. также

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
