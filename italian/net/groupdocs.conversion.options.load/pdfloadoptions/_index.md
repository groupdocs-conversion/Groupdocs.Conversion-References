---
title: "PdfLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Pdf."
type: docs
weight: 2740
url: /it/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Opzioni per il caricamento di documenti Pdf.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Inizializza una nuova istanza della classe [`PdfLoadOptions`](../pdfloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Rimuove le proprietà dei metadati integrate dal documento. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Rimuove le proprietà dei metadati personalizzate dal documento. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Il valore predefinito è false |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Il valore predefinito è true |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento Pdf. Il carattere seguente verrà utilizzato se ne manca uno. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | Appiattisce tutti i campi del modulo PDF. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Sostituisce caratteri specifici durante la conversione del documento Pdf. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Trasforma i caratteri esistenti dopo il caricamento del documento e il completamento della sostituzione dei caratteri. Le trasformazioni dei caratteri possono modificare qualsiasi carattere nel documento, inclusi i caratteri caricati correttamente. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Nascondi le annotazioni nei documenti Pdf. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Abilita o disabilita la generazione della numerazione di pagina nel documento convertito. Predefinito: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Rimuovi i file incorporati. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | Rimuovi javascript. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Reimposta le cartelle dei caratteri prima di caricare il documento |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
