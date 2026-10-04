---
title: "WebConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones de conversión al tipo de archivo web."
type: docs
weight: 2320
url: /es/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Opciones de conversión al tipo de archivo web.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Inicializa una nueva instancia de la clase [`WebConvertOptions`](../webconvertoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | Especifica si se deben incrustar los recursos de fuentes dentro del HTML principal. El valor predeterminado es false. Nota: Si FixedLayout está configurado como true, los recursos de fuentes siempre se incrustarán. |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Si `true` se utilizará un diseño fijo, por ejemplo, elementos HTML posicionados absolutamente. Predeterminado: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Mostrar bordes de página al convertir a diseño fijo. El valor predeterminado es True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | Se aplica solo al convertir una presentación a [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) o [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm), y se ignora para cualquier otra conversión. Especifica si la presentación se convierte en una presentación HTML interactiva con transiciones de diapositivas y animaciones de formas, en lugar de la página HTML estática predeterminada. El valor predeterminado es false. |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Si `true`, la entrada se convierte primero a PDF y luego al formato deseado. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
