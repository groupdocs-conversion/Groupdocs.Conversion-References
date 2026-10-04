---
title: "WatermarkImageOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para establecer marca de agua en el documento convertido"
type: docs
weight: 2290
url: /es/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

Opciones para establecer marca de agua en el documento convertido

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | Crear la clase WatermarkOptions y establecer el texto de la marca de agua |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Escalar automáticamente la marca de agua. Si el valor es true, la posición y el tamaño se calculan automáticamente para ajustarse al tamaño de la página. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Indica que la marca de agua se aplica como fondo. Si el valor es true, la marca de agua se coloca en la parte inferior. Por defecto es false y la marca de agua se coloca en la parte superior. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Altura de la marca de agua |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | Marca de agua de imagen |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Posición izquierda de la marca de agua |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Ángulo de rotación de la marca de agua |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Posición superior de la marca de agua |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Transparencia de la marca de agua. Valor entre 0 y 1. El valor 0 es totalmente visible, el valor 1 es invisible. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Ancho de la marca de agua |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Clonar la instancia actual |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
