---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет параметры оптимизации PDF."
type: docs
weight: 2120
url: /ru/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Определяет параметры оптимизации PDF.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Инициализирует новый экземпляр класса [`PdfOptimizationOptions`](../pdfoptimizationoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Если CompressImages установлен в `true`, все изображения в документе перекомпрессируются. Сжатие определяется свойством ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Установить стратегию подмножества шрифтов |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Значение в процентах, где 100% — неизменное качество и размер изображения. Чтобы уменьшить размер изображения, установите это свойство меньше 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Связать дублирующие потоки |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Удалить неиспользуемые объекты |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Удалить неиспользуемые потоки |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Не встраивать шрифты, если установлено в true |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
