---
title: "WatermarkImageOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры настройки водяного знака в конвертируемом документе"
type: docs
weight: 2290
url: /ru/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

Параметры настройки водяного знака в конвертируемом документе

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | Создайте класс WatermarkOptions и задайте текст водяного знака |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Автоматически масштабировать водяной знак. Если значение равно true, позиция и размер автоматически рассчитываются, чтобы соответствовать размеру страницы. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Указывает, что водяной знак наносится как фон. Если значение равно true, водяной знак размещается внизу. По умолчанию false, и водяной знак размещается сверху. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Высота водяного знака |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | Изображение водяного знака |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Левая позиция водяного знака |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Угол вращения водяного знака |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Верхняя позиция водяного знака |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Прозрачность водяного знака. Значение от 0 до 1. Значение 0 — полностью видимый, значение 1 — невидимый. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Ширина водяного знака |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Клонировать текущий экземпляр |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
