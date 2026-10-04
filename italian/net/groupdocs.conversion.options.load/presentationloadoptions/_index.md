---
title: "PresentationLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Presentation."
type: docs
weight: 2770
url: /it/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Opzioni per il caricamento di documenti Presentation.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | Inizializza una nuova istanza della classe [`PresentationLoadOptions`](../presentationloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | Rimuove le proprietà dei metadati integrate dal documento. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | Rimuove le proprietà dei metadati personalizzate dal documento. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | Rappresenta il modo in cui i commenti vengono stampati con la diapositiva. Il valore predefinito è None. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Il valore predefinito è false |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Il valore predefinito è true |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | Carattere predefinito per il rendering della presentazione. Il carattere seguente verrà utilizzato se manca un carattere nella presentazione. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | Sostituisci caratteri specifici durante la conversione del documento Presentation. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | Rappresenta il modo in cui le note vengono stampate con la diapositiva. Il valore predefinito è None. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | Determina se la struttura del documento deve essere preservata durante la conversione in PDF (il valore predefinito è false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | Mostra le diapositive nascoste. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | Imposta il connettore del documento video |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
