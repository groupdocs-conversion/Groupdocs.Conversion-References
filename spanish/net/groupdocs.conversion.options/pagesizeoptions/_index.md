---
title: "PageSizeOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Representa opciones que admiten el tamaño de página."
type: docs
weight: 2990
url: /es/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Representa opciones que admiten el tamaño de página.

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Constructor predeterminado. Inicializa [`PageSize`](./pagesize) a [`Unset`](../pagesize/unset). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Altura de página en puntos que se aplicará antes de la conversión. Cuando se establece, [`PageSize`](./pagesize) se cambia automáticamente a [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Implementa [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Ancho de página en puntos que se aplicará antes de la conversión. Cuando se establece, [`PageSize`](./pagesize) se cambia automáticamente a [`Custom`](../pagesize/custom). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
