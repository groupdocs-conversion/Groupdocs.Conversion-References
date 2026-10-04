---
title: "BitmapInfo"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Objeto que contiene una matriz de píxeles e información de mapa de bits."
type: docs
weight: 70
url: /es/net/groupdocs.conversion.contracts/bitmapinfo/
---
## BitmapInfo class

Objeto que contiene una matriz de píxeles e información de mapa de bits.

```csharp
public class BitmapInfo : ValueObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.contracts/bitmapinfo/format) { get; } | Obtiene el formato de píxel del mapa de bits. |
| [Height](../../groupdocs.conversion.contracts/bitmapinfo/height) { get; } | Obtiene la altura del mapa de bits. |
| [PixelBytes](../../groupdocs.conversion.contracts/bitmapinfo/pixelbytes) { get; } | Obtiene la matriz de píxeles. |
| [Width](../../groupdocs.conversion.contracts/bitmapinfo/width) { get; } | Obtiene el ancho del bitmap. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/bitmapinfo/create)(byte[], int, int, PixelFormat) | Crear una nueva instancia de BitmapInfo |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [PixelFormat](bitmapinfo.pixelformat) | Describe la enumeración de formato de píxel |

### Ver también

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
