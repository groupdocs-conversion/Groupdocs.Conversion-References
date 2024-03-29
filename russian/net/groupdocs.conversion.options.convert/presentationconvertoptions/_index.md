---
title: PresentationConvertOptions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Описывает параметры для преобразования в тип файла презентации.
type: docs
weight: 1830
url: /ru/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

Описывает параметры для преобразования в тип файла презентации.

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | Инициализирует новый экземпляр[`PresentationConvertOptions`](../presentationconvertoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Желаемый тип файла, в который должен быть преобразован входной документ. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Желаемый тип файла, в который должен быть преобразован входной документ. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Номер страницы, с которой начинается преобразование. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Список индексов страниц, которые необходимо преобразовать. Должен быть указан для преобразования определенных страниц. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Количество страниц для конвертации, начиная с`Номер страницы` . |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | Установите это свойство, если хотите защитить преобразованный документ паролем. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Специальные параметры водяного знака |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | Определяет уровень масштабирования в процентах. Значение по умолчанию: 100. Масштаб по умолчанию поддерживается до Microsoft Powerpoint 2010. Начиная с Microsoft Powerpoint 2013 масштаб по умолчанию больше не устанавливается на документ, вместо этого используется коэффициент масштабирования последнего открытого документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Копирует экземпляр текущих параметров. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* пространство имен [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
