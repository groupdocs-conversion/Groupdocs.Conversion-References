---
title: WordProcessingLoadOptions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Параметры загрузки документов WordProcessing.
type: docs
weight: 2100
url: /ru/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Параметры загрузки документов WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Инициализирует новый экземпляр[`WordProcessingLoadOptions`](../wordprocessingloadoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoFontSubstitution](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autofontsubstitution) { get; set; } | Если AutoFontSubstitution отключен, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. Если AutoFontSubstitution включен, GroupDocs.Conversion оценивает все связанные поля в FontInfo (Panose, Sig и т. д.) для отсутствующего шрифта и находит наиболее близкое соответствие среди доступных источников шрифта. Информация о шрифте для отсутствующего шрифта доступна в документе. Значение по умолчанию — True. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Опции закладок |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Шрифт по умолчанию для документа Word. Если шрифт отсутствует, будет использоваться следующий шрифт. |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Если EmbedTrueTypeFonts имеет значение true, GroupDocs.Conversion встраивает шрифты истинного типа в выходной документ. По умолчанию: false |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Замена определенных шрифтов при преобразовании документа Word. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Тип файла входного документа. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [HideComments](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidecomments) { get; set; } | Скрыть комментарии. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Скрыть разметку и отслеживать изменения для документов Word. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Сохранить исходное значение поля даты. По умолчанию: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Установить пароль для снятия защиты с защищенного документа. |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Указывает, сохранять ли поля формы Microsoft Word как поля формы в PDF или преобразовывать их в текст. По умолчанию false. |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Обновить поля после загрузки. По умолчанию: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Обновление макета страницы после загрузки. По умолчанию: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Указывает, использовать ли формирователь текста для лучшего отображения кернинга. По умолчанию false. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [LoadOptions](../loadoptions)
* пространство имен [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->