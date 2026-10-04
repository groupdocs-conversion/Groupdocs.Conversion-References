---
title: "WordProcessingLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de WordProcessing."
type: docs
weight: 2950
url: /es/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Opciones para cargar documentos de WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Inicializa una nueva instancia de la clase [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Cuando es true (valor predeterminado), los párrafos y ejecuciones cuyo texto es predominantemente de derecha a izquierda tendrán sus banderas bidi reparadas antes de la conversión. Esto coincide con la heurística que aplican Microsoft Word y LibreOffice y corrige la renderización de documentos en árabe/hebreo generados por creadores (en particular Google Docs) que emiten OOXML sin &lt;w:bidi/&gt; y con &lt;w:rtl w:val="0"/&gt; en ejecuciones que contienen solo script RTL. Establezca a false para preservar la interpretación estricta de OOXML del marcado de origen. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Opciones de marcadores |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Elimina las propiedades de metadatos incorporadas del documento. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Elimina las propiedades de metadatos personalizadas del documento. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Especifica cómo deben mostrarse los comentarios en el documento de salida. El valor predeterminado es ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) El valor predeterminado es falso |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) El valor predeterminado es verdadero |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Establece la fuente predeterminada para un documento WordProcessing. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Valor predeterminado: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Si EmbedTrueTypeFonts es verdadero, GroupDocs.Conversion incrusta fuentes TrueType en el documento de salida. Valor predeterminado: verdadero |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Sustituye automáticamente fuentes faltantes basándose en FontConfig del sistema. Valor predeterminado: falso. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Sustituye automáticamente fuentes faltantes basándose en FontInfo del documento. Valor predeterminado: falso. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Sustituye automáticamente fuentes faltantes basándose en el nombre de la fuente. Valor predeterminado: falso. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Sustituye fuentes específicas al convertir un documento WordsProcessing. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Transforma las fuentes existentes después de que la carga del documento y la sustitución de fuentes se completen. Las transformaciones de fuentes pueden modificar cualquier fuente en el documento, incluidas las fuentes que se cargaron correctamente. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Oculta el marcado y el seguimiento de cambios para documentos Word. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Establece opciones de guionado para documentos WordProcessing. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Mantiene el valor original del campo de fecha. Valor predeterminado: falso |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Configuración de márgenes de página |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Habilita o deshabilita la generación de numeración de páginas en el documento convertido. Valor predeterminado: falso |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Establece la contraseña para desproteger el documento protegido. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Determina si la estructura del documento debe preservarse al convertir a PDF (el valor predeterminado es falso). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Especifica si se deben preservar los campos de formulario de Microsoft Word como campos de formulario en PDF o convertirlos a texto. El valor predeterminado es falso. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Muestra el nombre completo del comentarista en los comentarios. El valor predeterminado es falso. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Configuración de tamaño de página |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Actualiza los campos después de la carga. Valor predeterminado: falso |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Actualiza el diseño de página después de la carga. Valor predeterminado: falso |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Especifica si se debe usar un modelador de texto para una mejor visualización del kerning. El valor predeterminado es falso. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Observaciones

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Gestiona fuentes faltantes/no disponibles usando FontSubstitutes, DefaultFont y sustitución del sistema

• Orden de procesamiento: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Modifica cualquier fuente existente en el documento cargado usando FontReplacements

• Se aplica después de que se complete toda la sustitución de fuentes

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
