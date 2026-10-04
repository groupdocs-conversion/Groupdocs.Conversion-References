---
title: "Прямоугольник"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Представляет прямоугольник, определённый его сторонами, для целей обрезки."
type: docs
weight: 580
url: /ru/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Представляет прямоугольник, определённый его сторонами, для целей обрезки.

```csharp
public sealed class Rectangle : ValueObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Инициализирует новый экземпляр структуры [`Rectangle`](../rectangle) с указанными гранями. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Получает нижнюю грань прямоугольника. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Получает высоту прямоугольника на основе верхней и нижней граней. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Получает левую грань прямоугольника. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Получает правую грань прямоугольника. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Получает верхнюю грань прямоугольника. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Получает ширину прямоугольника на основе левой и правой граней. |

## Методы

| Имя | Описание |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Создаёт обрезанную версию текущего прямоугольника, удаляя указанные отступы. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Возвращает строковое представление прямоугольника. |

### См. также

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
