---
title: WordProcessingConvertOptions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Параметры для преобразования в тип файла WordProcessing.
type: docs
weight: 1810
url: /ru/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Параметры для преобразования в тип файла WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Инициализирует новый экземпляр[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Желаемый DPI страницы после преобразования. Разрешение по умолчанию: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Желаемый тип файла, в который должен быть преобразован входной документ. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Желаемый тип файла, в который должен быть преобразован входной документ. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Желаемая высота страницы после преобразования. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Требуемое нижнее поле страницы в пикселях после преобразования. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Желаемое левое поле страницы в пикселях после преобразования. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Требуемое правое поле страницы в пикселях после преобразования. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Требуемое верхнее поле страницы в пикселях после преобразования. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Номер страницы, с которой начинается преобразование. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Желаемая ориентация страницы после преобразования |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Список индексов страниц, которые необходимо преобразовать. Должен быть указан для преобразования конкретных страниц. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Количество страниц для конвертации, начиная с`Номер страницы` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Желаемый размер страницы после преобразования |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Установите это свойство, если хотите защитить преобразованный документ паролем. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Режим распознавания при конвертации из pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Специальные параметры преобразования RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Специальные параметры водяного знака |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Желаемая ширина страницы после преобразования. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Определяет уровень масштабирования в процентах. Значение по умолчанию: 100. Масштаб по умолчанию поддерживается до Microsoft Word 2010. Начиная с Microsoft Word 2013 масштаб по умолчанию больше не устанавливается на документ, вместо этого используется коэффициент масштабирования последнего открытого документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Копирует экземпляр текущих параметров. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* пространство имен [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
