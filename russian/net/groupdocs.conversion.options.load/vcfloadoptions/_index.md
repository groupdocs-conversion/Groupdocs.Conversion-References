---
title: "VcfLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки документов Vcf."
type: docs
weight: 2890
url: /ru/net/groupdocs.conversion.options.load/vcfloadoptions/
---
## VcfLoadOptions class

Параметры загрузки документов Vcf.

```csharp
public sealed class VcfLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VcfLoadOptions](vcfloadoptions)() | Инициализирует новый экземпляр класса [`VcfLoadOptions`](../vcfloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.load/vcfloadoptions/encoding) { get; set; } | Получает или задает кодировку, которая будет использоваться при загрузке Vcf‑документа. По умолчанию — Encoding.Default. |
| [Format](../../groupdocs.conversion.options.load/vcfloadoptions/format) { get; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
