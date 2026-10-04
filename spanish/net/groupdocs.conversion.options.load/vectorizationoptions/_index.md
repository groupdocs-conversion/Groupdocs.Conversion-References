---
title: "VectorizationOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para vectorizar imágenes."
type: docs
weight: 2900
url: /es/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Opciones para vectorizar imágenes.

```csharp
public class VectorizationOptions : ValueObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Constructor predeterminado para VectorizationOptions. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo. El valor predeterminado es blanco transparente. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Obtiene o establece el número máximo de colores usados para cuantizar una imagen. El valor predeterminado es 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Habilita la vectorización de imágenes. Predeterminado es falso. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Obtiene o establece la dimensión máxima de la imagen determinada por la multiplicación del ancho y la altura de la imagen. El tamaño de la imagen se escalará según esta propiedad. El valor predeterminado es 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Obtiene o establece el ancho de línea. El valor de este parámetro se ve afectado por la escala gráfica. El valor predeterminado es 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Establece la severidad del suavizado de trazado de imagen |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
