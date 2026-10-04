---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Представляет сопоставление поддерживаемых пар преобразования для конкретного формата исходного файла"
type: docs
weight: 510
url: /ru/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Представляет сопоставление поддерживаемых пар преобразования для конкретного формата исходного файла

```csharp
public sealed class PossibleConversions : ValueObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Все типы целевых файлов и флаг primary/secondary IEnumerable из [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Возвращает целевое преобразование для указанного типа целевого файла (2 индексатора) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Предопределённые параметры загрузки, которые могут использоваться для преобразования из текущего типа |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Основные типы целевых файлов |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Вторичные типы целевых файлов |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Форматы исходных файлов |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
