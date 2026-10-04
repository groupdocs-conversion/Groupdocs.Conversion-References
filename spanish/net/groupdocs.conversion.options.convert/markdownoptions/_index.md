---
title: "MarkdownOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para la conversión al tipo de archivo markdown."
type: docs
weight: 2010
url: /es/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Opciones para la conversión al tipo de archivo markdown.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Inicializa una nueva instancia de la clase [`MarkdownOptions`](../markdownoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Exportar imágenes como base64. El valor predeterminado es true. Se ignora cuando [`ImageSavingCallback`](./imagesavingcallback) está configurado. |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Callback invocado una vez por imagen al guardar Markdown. Permite al llamador almacenar imágenes externamente y sustituir el URI incrustado en el documento. Tiene prioridad sobre [`ExportImagesAsBase64`](./exportimagesasbase64) cuando no es nulo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
