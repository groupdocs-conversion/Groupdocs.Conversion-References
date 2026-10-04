---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры векторизации изображений."
type: docs
weight: 2900
url: /ru/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Параметры векторизации изображений.

```csharp
public class VectorizationOptions : ValueObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Конструктор по умолчанию для VectorizationOptions. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Получает или задаёт цвет фона. Значение по умолчанию — прозрачный белый. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Получает или задаёт максимальное количество цветов, используемых для квантизации изображения. Значение по умолчанию — 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Включает векторизацию изображений. По умолчанию — false. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Получает или задаёт максимальное измерение изображения, определяемое произведением ширины и высоты изображения. Размер изображения будет масштабироваться на основе этого свойства. Значение по умолчанию — 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Получает или задаёт ширину линии. Значение этого параметра зависит от масштаба графики. Значение по умолчанию — 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Устанавливает степень сглаживания трассировки изображения |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
