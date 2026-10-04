---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры настройки текстового водяного знака в конвертируемом документе"
type: docs
weight: 2310
url: /ru/net/groupdocs.conversion.options.convert/watermarktextoptions/
---
## WatermarkTextOptions class

Параметры настройки текстового водяного знака в конвертируемом документе

```csharp
public sealed class WatermarkTextOptions : WatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WatermarkTextOptions](watermarktextoptions)(string) | Создайте класс WatermarkOptions и задайте текст водяного знака |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Автоматически масштабировать водяной знак. Если значение равно true, позиция и размер автоматически рассчитываются, чтобы соответствовать размеру страницы. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Указывает, что водяной знак наносится как фон. Если значение равно true, водяной знак размещается внизу. По умолчанию false, и водяной знак размещается сверху. |
| [Color](../../groupdocs.conversion.options.convert/watermarktextoptions/color) { get; set; } | Цвет шрифта водяного знака, если применяется текстовый водяной знак |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Высота водяного знака |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Левая позиция водяного знака |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Угол вращения водяного знака |
| [Text](../../groupdocs.conversion.options.convert/watermarktextoptions/text) { get; } | Текст водяного знака |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Верхняя позиция водяного знака |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Прозрачность водяного знака. Значение от 0 до 1. Значение 0 — полностью видимый, значение 1 — невидимый. |
| [WatermarkFont](../../groupdocs.conversion.options.convert/watermarktextoptions/watermarkfont) { get; set; } | Шрифт водяного знака, если применяется текстовый водяной знак |
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
