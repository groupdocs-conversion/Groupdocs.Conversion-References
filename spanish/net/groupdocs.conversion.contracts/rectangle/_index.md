---
title: "Rectángulo"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Representa un rectángulo definido por sus bordes para propósitos de recorte."
type: docs
weight: 580
url: /es/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Representa un rectángulo definido por sus bordes para propósitos de recorte.

```csharp
public sealed class Rectangle : ValueObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Inicializa una nueva instancia de la estructura [`Rectangle`](../rectangle) con los bordes especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Obtiene el borde inferior del rectángulo. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Obtiene la altura del rectángulo basada en los bordes superior e inferior. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Obtiene el borde izquierdo del rectángulo. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Obtiene el borde derecho del rectángulo. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Obtiene el borde superior del rectángulo. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Obtiene el ancho del rectángulo basado en los bordes izquierdo y derecho. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Crea una versión recortada del rectángulo actual eliminando los márgenes especificados. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Devuelve una representación en cadena del rectángulo. |

### Ver también

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
