---
title: "DiagramLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de Diagrama."
type: docs
weight: 2470
url: /es/net/groupdocs.conversion.options.load/diagramloadoptions/
---
## DiagramLoadOptions class

Opciones para cargar documentos de Diagrama.

```csharp
public sealed class DiagramLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DiagramLoadOptions](diagramloadoptions)() | Inicializa una nueva instancia de la clase [`DiagramLoadOptions`](../diagramloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/diagramloadoptions/defaultfont) { get; set; } | Fuente predeterminada para el documento Diagram. La siguiente fuente se utilizará si falta una fuente. |
| [Format](../../groupdocs.conversion.options.load/diagramloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
