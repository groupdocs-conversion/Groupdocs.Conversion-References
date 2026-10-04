---
title: "BitmapInfo"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Объект, содержащий массив пикселей и информацию о битмапе."
type: docs
weight: 70
url: /ru/net/groupdocs.conversion.contracts/bitmapinfo/
---
## BitmapInfo class

Объект, содержащий массив пикселей и информацию о битмапе.

```csharp
public class BitmapInfo : ValueObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.conversion.contracts/bitmapinfo/format) { get; } | Получает формат пикселей битмапа. |
| [Height](../../groupdocs.conversion.contracts/bitmapinfo/height) { get; } | Получает высоту битмапа. |
| [PixelBytes](../../groupdocs.conversion.contracts/bitmapinfo/pixelbytes) { get; } | Получает массив пикселей. |
| [Width](../../groupdocs.conversion.contracts/bitmapinfo/width) { get; } | Получает ширину bitmap. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/bitmapinfo/create)(byte[], int, int, PixelFormat) | Создать новый экземпляр BitmapInfo |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [PixelFormat](bitmapinfo.pixelformat) | Описывает перечисление форматов пикселей |

### См. также

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
