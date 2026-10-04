---
title: "TxtLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos Txt."
type: docs
weight: 2870
url: /es/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Opciones para cargar documentos Txt.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Inicializa una nueva instancia de la clase [`TxtLoadOptions`](../txtloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Fuente a usar al renderizar contenido de texto plano durante la conversión. Dado que los archivos TXT no contienen información de fuentes, esta propiedad especifica la fuente de visualización para el contenido de texto. Predeterminado: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto plano. El valor predeterminado es true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Obtiene o establece la codificación que se usará al cargar un documento Txt. Puede ser null. El valor predeterminado es null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Obtiene o establece la opción preferida para el manejo de espacios iniciales. El valor predeterminado es [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Configuración de márgenes de página |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Configuración de tamaño de página |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Obtiene o establece la opción preferida para el manejo de espacios finales. El valor predeterminado es [`Trim`](../txttrailingspacesoptions/trim). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Observaciones

**Font Configuration for Plain Text:**

Dado que los archivos TXT no contienen información de fuentes, use DefaultTextFont para especificar

la fuente para renderizar el contenido de texto plano durante la conversión.

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
