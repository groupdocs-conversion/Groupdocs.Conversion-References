---
title: "CadLayoutScope"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Представляет, какие пространства чертежа выбирает CAD‑конверсия: модельное пространство, макеты листового пространства или оба."
type: docs
weight: 2420
url: /ru/net/groupdocs.conversion.options.load/cadlayoutscope/
---
## CadLayoutScope class

Представляет, какие чертёжные пространства выбирает преобразование CAD: модельное пространство, макеты листового пространства или оба.

```csharp
public class CadLayoutScope : Enumeration
```

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Возвращает строку, представляющую текущий объект. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Both](../../groupdocs.conversion.options.load/cadlayoutscope/both) | Выбирает модельное пространство и каждый макет листового пространства. Это значение по умолчанию и оно не ограничивает конверсию: чертеж отображается точно так же, как если бы область не была указана. |
| static readonly [Layouts](../../groupdocs.conversion.options.load/cadlayoutscope/layouts) | Выбирает только макеты листового пространства. Модельное пространство исключено. |
| static readonly [Model](../../groupdocs.conversion.options.load/cadlayoutscope/model) | Выбирает только модельное пространство. |

### См. также

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
