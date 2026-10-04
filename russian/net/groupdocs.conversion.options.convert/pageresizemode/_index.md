---
title: "PageResizeMode"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Указывает, как следует масштабировать содержимое при изменении размера страницы"
type: docs
weight: 2050
url: /ru/net/groupdocs.conversion.options.convert/pageresizemode/
---
## PageResizeMode class

Указывает, как следует масштабировать содержимое при изменении размера страницы

```csharp
public sealed class PageResizeMode : Enumeration
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
| static [AlignTopLeft](../../groupdocs.conversion.options.convert/pageresizemode/aligntopleft) | Масштабирование не применяется. Содержимое выровнено по верхнему левому углу. |
| static [ScaleToFill](../../groupdocs.conversion.options.convert/pageresizemode/scaletofill) | Растянуть содержимое, чтобы заполнить всю страницу. Может исказить соотношение сторон. |
| static [ScaleToFit](../../groupdocs.conversion.options.convert/pageresizemode/scaletofit) | Масштабировать содержимое пропорционально, чтобы вписать его во всю страницу без выхода за границы. Может привести к появлению пустого пространства. |
| static [ScaleToHeight](../../groupdocs.conversion.options.convert/pageresizemode/scaletoheight) | Масштабировать содержимое пропорционально, чтобы соответствовать высоте страницы. Ширина может выйти за границы и будет обрезана. |
| static [ScaleToWidth](../../groupdocs.conversion.options.convert/pageresizemode/scaletowidth) | Масштабировать содержимое пропорционально, чтобы соответствовать ширине страницы. Высота может выйти за границы и будет обрезана. |

### См. также

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
