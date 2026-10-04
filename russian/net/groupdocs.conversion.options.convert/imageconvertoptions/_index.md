---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры конвертации в тип файла Image."
type: docs
weight: 1950
url: /ru/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Параметры конвертации в тип файла Image.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Создаёт новый экземпляр класса [`ImageConvertOptions`](../imageconvertoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Устанавливает цвет фона, если он поддерживается исходным форматом. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Регулирует яркость изображения. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Если включено, ограничивает разрешение рендеринга PDF для каждой страницы до нативного растрового разрешения страницы, так что страница никогда не рендерится с более высоким DPI, чем фактически содержит встроенное изображение, и выводит эту страницу с её нативными (меньшими) пиксельными размерами и нативным DPI в окончательном результате вместо увеличения до запрошенного DPI. Это влияет только на страницы, доминирующие изображениями (сканами); страницы с текстом или векторным содержимым никогда не смягчаются и выводятся с запрошенным DPI. Пропускается, если явно задан выводной [`Width`](./width) или [`Height`](./height). По умолчанию `false` (ограничения нет; каждая страница рендерится и выводится с запрошенным DPI). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Регулирует контраст изображения. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Обрезать область растрового изображения после конвертации. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Режим отражения изображения. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Желаемый тип файла, в который следует преобразовать входной документ. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Реализует [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Регулирует гамму изображения. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Указывает, следует ли преобразовать в изображение в градациях серого. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Желаемая высота изображения после конвертации. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Желаемое горизонтальное разрешение изображения после конвертации. Разрешение по умолчанию — разрешение входного файла или 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Параметры конвертации, специфичные для JPEG. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Нижняя граница по каждой оси, применяемая к ограниченному DPI рендеринга, когда включён [`CapResolutionToPageContent`](./capresolutiontopagecontent). Ограниченный DPI никогда не опускается ниже этого значения. По умолчанию `0` (нет нижней границы). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Реализует [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Реализует [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Реализует [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Параметры конвертации, специфичные для PSD. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Угол поворота изображения. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Параметры преобразования, специфичные для Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Если `true`, входные данные сначала конвертируются в PDF, а затем в требуемый формат. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Желаемое вертикальное разрешение изображения после преобразования. Разрешение по умолчанию — разрешение входного файла или 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Реализует [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Параметры преобразования, специфичные для Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Желаемая ширина изображения после преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Клонирует текущий экземпляр параметров. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
