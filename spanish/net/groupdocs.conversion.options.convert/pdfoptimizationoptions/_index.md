---
title: "PdfOptimizationOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define las opciones de optimización PDF."
type: docs
weight: 2120
url: /es/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Define las opciones de optimización PDF.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Inicializa una nueva instancia de la clase [`PdfOptimizationOptions`](../pdfoptimizationoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Si CompressImages se establece en `true`, todas las imágenes del documento se vuelven a comprimir. La compresión está definida por la propiedad ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Establecer estrategia de subconjunto de fuentes |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Valor en porcentaje donde 100 % representa calidad y tamaño de imagen sin cambios. Para reducir el tamaño de la imagen, establezca esta propiedad a menos de 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Vincular flujos duplicados |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Eliminar objetos no utilizados |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Eliminar flujos no utilizados |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | No incrustar fuentes si se establece a true |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
