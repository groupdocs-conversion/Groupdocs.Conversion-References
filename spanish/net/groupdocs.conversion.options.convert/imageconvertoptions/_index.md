---
title: ImageConvertOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones para conversión a tipo de archivo Imagen.
type: docs
weight: 1470
url: /es/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opciones para conversión a tipo de archivo Imagen.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Inicializa una nueva instancia de[`ImageConvertOptions`](../imageconvertoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Establece el color de fondo donde lo admita el formato de origen |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Ajusta el brillo de la imagen. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Ajusta el contraste de la imagen. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Modo de volteo de imagen. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Ajusta la gamma de la imagen. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indica si convertir a imagen en escala de grises. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Altura deseada de la imagen después de la conversión. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Resolución horizontal de imagen deseada después de la conversión. La resolución predeterminada es la resolución del archivo de entrada o 96 ppp. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Opciones de conversión específicas de JPEG. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | El número de página desde el que iniciar la conversión. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La lista de índices de página que se van a convertir. Debe especificarse para convertir páginas específicas. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Número de páginas para convertir a partir de`Número de página` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Opciones de conversión específicas de Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Ángulo de rotación de la imagen. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Opciones de conversión específicas de Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Si`verdadero` la entrada primero se convierte a PDF y luego al formato deseado. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Resolución vertical de imagen deseada después de la conversión. La resolución predeterminada es la resolución del archivo de entrada o 96 ppp. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opciones específicas de marca de agua |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Opciones de conversión específicas de Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Ancho de imagen deseado después de la conversión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia de opciones actual. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* espacio de nombres [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
