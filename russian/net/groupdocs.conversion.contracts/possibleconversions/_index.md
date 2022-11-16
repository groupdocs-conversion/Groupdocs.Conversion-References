---
title: PossibleConversions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Представляет сопоставление какие пары преобразования поддерживаются для определенного формата исходного файла
type: docs
weight: 370
url: /ru/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Представляет сопоставление, какие пары преобразования поддерживаются для определенного формата исходного файла

```csharp
public sealed class PossibleConversions : ValueObject
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Все целевые типы файлов и основной/дополнительный флаг  IEnumerable из[`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Возвращает целевое преобразование для указанного целевого файла type (2 indexers) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Предопределенные параметры загрузки, которые можно использовать для преобразования текущего типа |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Основные типы целевых файлов |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Типы вторичных целевых файлов |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Форматы исходных файлов |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [ValueObject](../valueobject)
* пространство имен [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->