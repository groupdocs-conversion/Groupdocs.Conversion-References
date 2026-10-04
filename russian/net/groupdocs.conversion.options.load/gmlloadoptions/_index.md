---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки Gml‑документов."
type: docs
weight: 2550
url: /ru/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Параметры загрузки Gml‑документов.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Инициализирует новый экземпляр класса [`GmlLoadOptions`](../gmlloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Тип файла входного документа. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Устанавливает желаемую высоту страницы при конвертации GIS‑документа. Значение по умолчанию — 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Определяет, разрешено ли Conversion загружать XML‑схему из Интернета. Если установлено false, схемы с абсолютными URI, которые не начинаются с ‘file://’, не будут загружаться. По умолчанию false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Определяет, разрешено ли Conversion разбирать атрибуты в файле Gml, когда XML‑схема отсутствует или не может быть загружена. Если установлено true, чтение Conversion не требует наличия XML‑схемы. По умолчанию false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Список пар URI, разделённых пробелами. Первый URI в каждой паре — URI пространства имён, второй URI — путь к XML‑схеме этого пространства имён. Если установлено null, Conversion попытается прочитать schemaLocation из корневого элемента документа. По умолчанию null. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Устанавливает желаемую ширину страницы при конвертации GIS‑документа. Значение по умолчанию — 1000. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
