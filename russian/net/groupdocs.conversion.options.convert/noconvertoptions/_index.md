---
title: "NoConvertOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Специальный класс параметров конвертации, который инструктирует конвертер копировать исходный документ без какой-либо обработки"
type: docs
weight: 2020
url: /ru/net/groupdocs.conversion.options.convert/noconvertoptions/
---
## NoConvertOptions class

Специальный класс параметра конвертации, который инструктирует конвертер копировать исходный документ без какой-либо обработки

```csharp
public sealed class NoConvertOptions : ConvertOptions<FileType>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NoConvertOptions](noconvertoptions)() | Инициализирует новый экземпляр класса [`NoConvertOptions`](../noconvertoptions) с форматом по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Желаемый тип файла, в который следует преобразовать входной документ. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Реализует [`Format`](../iconvertoptions/format) |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Клонирует текущий экземпляр параметров. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
