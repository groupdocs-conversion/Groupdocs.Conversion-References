---
title: "PdfOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para la conversión al tipo de archivo Pdf."
type: docs
weight: 2130
url: /es/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Opciones para la conversión al tipo de archivo Pdf.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptions](pdfoptions)() | Inicializa una nueva instancia de la clase [`PdfOptions`](../pdfoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Metainformación del documento PDF. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | Opciones de formato PDF |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Convertir un PDF de espacio de color RGB a escala de grises |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Linealiza el documento PDF para la web |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | Opciones de optimización PDF |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Establece el formato PDF del documento convertido. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Elimina la conformidad Pdf-A |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
