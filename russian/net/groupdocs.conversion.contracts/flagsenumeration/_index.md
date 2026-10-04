---
title: "FlagsEnumeration"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Представляет абстрактный базовый класс для создания перечислений, поддерживающих побитовые операции флагов."
type: docs
weight: 220
url: /ru/net/groupdocs.conversion.contracts/flagsenumeration/
---
## FlagsEnumeration class

Представляет абстрактный базовый класс для создания перечислений, поддерживающих побитовые операции флагов.

```csharp
public abstract class FlagsEnumeration : Enumeration
```

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Проверяет, имеет ли текущий флаг указанный флаг. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Проверяет, имеет ли текущий флаг указанное значение. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Преобразует текущий объект в строку. |
| static [Combine&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/combine)(T, T) | Объединяет два перечисления флагов в одно. |

### См. также

* class [Enumeration](../enumeration)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
