---
title: WordProcessingConvertOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones para la conversión a tipo de archivo WordProcessing.
type: docs
weight: 2000
url: /es/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Opciones para la conversión a tipo de archivo WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Inicializa una nueva instancia de[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Página deseada DPI después de la conversión. La resolución por defecto es: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Alto de página deseado después de la conversión. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Margen inferior de la página deseado en píxeles después de la conversión. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Margen izquierdo de la página deseada en píxeles después de la conversión. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Margen derecho de la página deseada en píxeles después de la conversión. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Margen superior de página deseado en píxeles después de la conversión. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | El número de página desde el que iniciar la conversión. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Orientación de página deseada después de la conversión |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La lista de índices de página que se van a convertir. Debe especificarse para convertir páginas específicas. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Número de páginas para convertir a partir de`Número de página` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Tamaño de página deseado después de la conversión |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Configure esta propiedad si desea proteger el documento convertido con una contraseña. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Modo de reconocimiento al convertir de pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Opciones de conversión específicas de RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opciones específicas de marca de agua |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Ancho de página deseado después de la conversión. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. El zoom predeterminado es compatible hasta Microsoft Word 2010. A partir de Microsoft Word 2013, el zoom predeterminado ya no está configurado para documento, sino que parece usar el factor de zoom del último documento que se abrió. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia de opciones actual. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* espacio de nombres [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
