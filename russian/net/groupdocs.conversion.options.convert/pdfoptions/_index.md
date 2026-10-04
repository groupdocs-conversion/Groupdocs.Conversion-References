---
title: "PdfOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры конвертации в тип файла Pdf."
type: docs
weight: 2130
url: /ru/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Параметры конвертации в тип файла Pdf.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptions](pdfoptions)() | Инициализирует новый экземпляр класса [`PdfOptions`](../pdfoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Метаданные PDF‑документа. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | Параметры форматирования PDF |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Преобразовать PDF из цветового пространства RGB в градации серого |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Линеаризует PDF‑документ для веба |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | Параметры оптимизации PDF |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Устанавливает формат PDF преобразованного документа. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Удаляет соответствие PDF/A |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Указывает уровень масштабирования в процентах. По умолчанию 100. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
