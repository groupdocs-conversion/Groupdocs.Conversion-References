---
title: "ImageConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para la conversión al tipo de archivo Imagen."
type: docs
weight: 1950
url: /es/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opciones para la conversión al tipo de archivo Imagen.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Inicializa una nueva instancia de la clase [`ImageConvertOptions`](../imageconvertoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Establece el color de fondo donde lo admite el formato de origen. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Ajusta el brillo de la imagen. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Cuando se establece, limita la resolución de renderizado PDF por página a la resolución raster nativa de la página, de modo que una página nunca se renderiza a un DPI superior al que realmente contiene su imagen incrustada, y emite esa página con sus dimensiones de píxel nativas (más pequeñas) y DPI nativo en la salida final en lugar de inflarla al DPI solicitado. Solo se ven afectadas las páginas dominadas por imágenes (escaneos); las páginas con texto o contenido vectorial nunca se suavizan y se emiten al DPI solicitado. Se omite cuando se define explícitamente una salida [`Width`](./width) o [`Height`](./height). El valor predeterminado es `false` (sin limitación; cada página se renderiza y emite al DPI solicitado). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Ajusta el contraste de la imagen. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Recortar el área de la imagen raster después de la conversión. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Modo de volteo de imagen. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Ajusta la gamma de la imagen. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indica si se debe convertir a una imagen en escala de grises. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Altura deseada de la imagen después de la conversión. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Resolución horizontal deseada de la imagen después de la conversión. La resolución predeterminada es la resolución del archivo de entrada o 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Opciones de conversión específicas de Jpeg. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Límite inferior por eje aplicado al DPI de renderizado limitado cuando [`CapResolutionToPageContent`](./capresolutiontopagecontent) está habilitado. El DPI limitado nunca se reduce por debajo de este valor. El valor predeterminado es `0` (sin límite inferior). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Opciones de conversión específicas de Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Ángulo de rotación de la imagen. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Opciones de conversión específicas de Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Si `true`, la entrada se convierte primero a PDF y luego al formato deseado. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Resolución vertical deseada de la imagen después de la conversión. La resolución predeterminada es la resolución del archivo de entrada o 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Opciones de conversión específicas de Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Ancho deseado de la imagen después de la conversión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
