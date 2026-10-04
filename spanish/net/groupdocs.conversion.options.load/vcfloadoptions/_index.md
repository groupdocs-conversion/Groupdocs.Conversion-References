---
title: "VcfLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos Vcf."
type: docs
weight: 2890
url: /es/net/groupdocs.conversion.options.load/vcfloadoptions/
---
## VcfLoadOptions class

Opciones para cargar documentos Vcf.

```csharp
public sealed class VcfLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VcfLoadOptions](vcfloadoptions)() | Inicializa una nueva instancia de la clase [`VcfLoadOptions`](../vcfloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.load/vcfloadoptions/encoding) { get; set; } | Obtiene o establece la codificación que se usará al cargar el documento Vcf. El valor predeterminado es Encoding.Default. |
| [Format](../../groupdocs.conversion.options.load/vcfloadoptions/format) { get; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
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
