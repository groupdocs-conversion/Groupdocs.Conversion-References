---
title: WatermarkOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones para configurar la marca de agua en el documento convertido
type: docs
weight: 1960
url: /es/net/groupdocs.conversion.options.convert/watermarkoptions/
---
## WatermarkOptions class

Opciones para configurar la marca de agua en el documento convertido

```csharp
public abstract class WatermarkOptions : ValueObject, ICloneable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Escala automática de la marca de agua. Si el valor es verdadero, la posición y el tamaño se calculan automáticamente para ajustarse al tamaño de la página. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Indica que la marca de agua está estampada como fondo. Si el valor es verdadero, la marca de agua se coloca en la parte inferior. Por defecto es falso y la marca de agua se coloca encima. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Altura de marca de agua |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Marca de agua posición izquierda |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Ángulo de rotación de marca de agua |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Posición superior de marca de agua |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Transparencia de marca de agua. Valor entre 0 y 1. El valor 0 es completamente visible, el valor 1 es invisible. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Ancho de marca de agua |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Clonar instancia actual |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* espacio de nombres [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
