---
title: "CadLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos CAD."
type: docs
weight: 2430
url: /es/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Opciones para cargar documentos CAD.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Inicializa una nueva instancia de la clase [`CadLoadOptions`](../cadloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Obtiene o establece un color de fondo. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Obtiene o establece las fuentes CTB. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Obtiene o establece el color de primer plano. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Obtiene o establece el tipo de dibujo. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Especifica qué diseños CAD se convertirán |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Obtiene o establece qué espacios de dibujo se convierten. Por defecto es [`Both`](../cadlayoutscope/both), lo que no restringe la conversión. Se ignora cuando se proporciona [`LayoutNames`](./layoutnames), porque los nombres de diseño explícitos siempre prevalecen. Un valor `null` se trata como [`Both`](../cadlayoutscope/both). |

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
