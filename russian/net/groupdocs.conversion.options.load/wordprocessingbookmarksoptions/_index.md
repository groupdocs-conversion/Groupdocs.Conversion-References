---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры обработки закладок в WordProcessing"
type: docs
weight: 2930
url: /ru/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

Параметры обработки закладок в WordProcessing

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | Указывает уровень по умолчанию в структуре документа, на котором отображаются закладки Word. По умолчанию 0. Допустимый диапазон от 0 до 9. |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | Указывает, сколько уровней в структуре документа будет развернуто при просмотре файла. По умолчанию 0. Допустимый диапазон от 0 до 9. Обратите внимание, что эта опция не будет работать при сохранении в XPS. |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | Указывает, сколько уровней заголовков (абзацев, отформатированных стилями Heading) включать в структуру документа. По умолчанию 0. Допустимый диапазон от 0 до 9. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
