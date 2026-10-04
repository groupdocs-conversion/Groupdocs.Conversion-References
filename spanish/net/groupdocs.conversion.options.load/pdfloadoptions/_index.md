---
title: "PdfLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos Pdf."
type: docs
weight: 2740
url: /es/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Opciones para cargar documentos Pdf.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Inicializa una nueva instancia de la clase [`PdfLoadOptions`](../pdfloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Elimina las propiedades de metadatos incorporadas del documento. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Elimina las propiedades de metadatos personalizadas del documento. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) El valor predeterminado es falso |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) El valor predeterminado es verdadero |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Fuente predeterminada para documentos Pdf. La siguiente fuente se usará si falta una fuente. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Valor predeterminado: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | Aplana todos los campos del formulario PDF. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Sustituye fuentes específicas al convertir un documento Pdf. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Transforma las fuentes existentes después de que la carga del documento y la sustitución de fuentes se completen. Las transformaciones de fuentes pueden modificar cualquier fuente en el documento, incluidas las fuentes que se cargaron correctamente. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Ocultar anotaciones en documentos Pdf. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Habilita o deshabilita la generación de numeración de páginas en el documento convertido. Valor predeterminado: falso |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Establece la contraseña para desproteger el documento protegido. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Eliminar archivos incrustados. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | Eliminar javascript. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Restablece las carpetas de fuentes antes de cargar el documento |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
