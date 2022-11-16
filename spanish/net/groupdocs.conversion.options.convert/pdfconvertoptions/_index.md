---
title: PdfConvertOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones de conversión a archivo tipo Pdf.
type: docs
weight: 1560
url: /es/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Opciones de conversión a archivo tipo Pdf.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IPageMarginConvertOptions, 
    IPageOrientationConvertOptions, IPageSizeConvertOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Inicializa una nueva instancia de[`PdfConvertOptions`](../pdfconvertoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | Página deseada DPI después de la conversión. La resolución por defecto es: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| [Height](../../groupdocs.conversion.options.convert/pdfconvertoptions/height) { get; set; } | Altura de página deseada en píxeles después de la conversión. |
| [MarginBottom](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginbottom) { get; set; } | Margen inferior de la página deseado en píxeles después de la conversión. |
| [MarginLeft](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginleft) { get; set; } | Margen izquierdo de la página deseada en píxeles después de la conversión. |
| [MarginRight](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginright) { get; set; } | Margen derecho de la página deseada en píxeles después de la conversión. |
| [MarginTop](../../groupdocs.conversion.options.convert/pdfconvertoptions/margintop) { get; set; } | Margen superior de página deseado en píxeles después de la conversión. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | El número de página desde el que iniciar la conversión. |
| [PageOrientation](../../groupdocs.conversion.options.convert/pdfconvertoptions/pageorientation) { get; set; } | Orientación de página deseada después de la conversión |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La lista de índices de página que se van a convertir. Debe especificarse para convertir páginas específicas. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Número de páginas para convertir a partir de`Número de página` . |
| [PageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/pagesize) { get; set; } | Tamaño de página deseado después de la conversión |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Configure esta propiedad si desea proteger el documento convertido con una contraseña. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Opciones de conversión específicas de PDF |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Rotación de página |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opciones específicas de marca de agua |
| [Width](../../groupdocs.conversion.options.convert/pdfconvertoptions/width) { get; set; } | Ancho de página deseado en píxeles después de la conversión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia de opciones actual. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* espacio de nombres [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->