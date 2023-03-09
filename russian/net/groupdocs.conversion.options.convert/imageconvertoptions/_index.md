---
title: ImageConvertOptions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Параметры для преобразования в тип файла изображения.
type: docs
weight: 1630
url: /ru/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Параметры для преобразования в тип файла изображения.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Инициализирует новый экземпляр[`ImageConvertOptions`](../imageconvertoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Устанавливает цвет фона, если это поддерживается исходным форматом |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Регулирует яркость изображения. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Настройка контрастности изображения. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Режим переворота изображения. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Желаемый тип файла, в который должен быть преобразован входной документ. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Желаемый тип файла, в который должен быть преобразован входной документ. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Настройка гаммы изображения. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Указывает, следует ли преобразовывать изображение в оттенки серого. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Требуемая высота изображения после преобразования. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Желаемое разрешение изображения по горизонтали после преобразования. Разрешение по умолчанию — это разрешение входного файла или 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Конкретные параметры преобразования Jpeg. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Номер страницы, с которой начинается преобразование. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Список индексов страниц, которые необходимо преобразовать. Должен быть указан для преобразования определенных страниц. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Количество страниц для конвертации, начиная с`Номер страницы` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Конкретные параметры преобразования Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Угол поворота изображения. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Специальные параметры преобразования Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Если`истинный` , ввод сначала преобразуется в PDF, а затем в желаемый формат. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Желаемое вертикальное разрешение изображения после преобразования. Разрешение по умолчанию — это разрешение входного файла или 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Специальные параметры водяного знака |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Конкретные параметры преобразования Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Желаемая ширина изображения после преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Копирует экземпляр текущих параметров. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* пространство имен [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
