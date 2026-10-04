---
title: "FontSubstitutionContext"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Describe una única sustitución de fuente que ocurrió al cargar o renderizar un documento de origen. Las instancias se pasan a OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /es/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Describe una única sustitución de fuente que ocurrió al cargar o renderizar un documento de origen. Las instancias se pasan a [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Crea un nuevo [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Nombre de la fuente referenciada por el documento de origen pero no disponible para el pipeline de conversión. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | El mensaje de sustitución exactamente como lo reporta la canalización de conversión, literalmente y sin analizar. Para documentos que exponen nombres de fuentes estructuralmente esto puede ser `null` (use [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); para otros lleva la descripción completa legible por humanos, que nombra tanto la fuente faltante como la fuente sustituta. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Nombre de archivo del documento fuente que se está convirtiendo. Cuando la fuente se proporcionó como un flujo que no es un FileStream, esto contiene un identificador generado en lugar de un nombre de archivo real. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Nombre de la fuente utilizada como sustituta. Puede ser `null` para documentos cuyo motor reporta la sustitución solo como texto descriptivo — en ese caso lea [`Reason`](./reason). |

### Ver también

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
