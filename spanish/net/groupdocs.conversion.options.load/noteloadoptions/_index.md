---
title: "NoteLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos One."
type: docs
weight: 2680
url: /es/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Opciones para cargar documentos One.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Inicializa una nueva instancia de la clase [`NoteLoadOptions`](../noteloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Fuente predeterminada para el documento Note. Se utilizará la siguiente fuente si falta alguna fuente. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Sustituye fuentes específicas al convertir el documento Note. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Establece la contraseña para desproteger el documento protegido. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
