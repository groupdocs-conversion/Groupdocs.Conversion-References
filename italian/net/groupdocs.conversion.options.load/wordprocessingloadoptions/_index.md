---
title: "WordProcessingLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti WordProcessing."
type: docs
weight: 2950
url: /it/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Opzioni per il caricamento di documenti WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Inizializza una nuova istanza della classe [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Quando è true (predefinito), i paragrafi e le run il cui testo è prevalentemente da destra a sinistra avranno i loro flag bidi riparati prima della conversione. Questo corrisponde all'euristica applicata da Microsoft Word e LibreOffice e corregge il rendering di documenti arabi/ebraici prodotti da generatori (in particolare Google Docs) che generano OOXML senza &lt;w:bidi/&gt; e con &lt;w:rtl w:val="0"/&gt; sulle run che contengono solo script RTL. Impostare a false per preservare un'interpretazione OOXML rigorosa del markup di origine. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Opzioni dei segnalibri |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Rimuove le proprietà dei metadati integrate dal documento. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Rimuove le proprietà dei metadati personalizzate dal documento. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Specifica come i commenti devono essere visualizzati nel documento di output. Il valore predefinito è ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Il valore predefinito è false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Il valore predefinito è true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Imposta il carattere predefinito per un documento WordProcessing. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Se EmbedTrueTypeFonts è true, GroupDocs.Conversion incorpora i caratteri TrueType nel documento di output. Predefinito: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Sostituisce automaticamente i caratteri mancanti in base a FontConfig nel sistema. Predefinito: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Sostituisce automaticamente i caratteri mancanti in base a FontInfo nel documento. Predefinito: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Sostituisce automaticamente i caratteri mancanti in base al nome del carattere. Predefinito: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Sostituisce caratteri specifici durante la conversione di un documento WordsProcessing. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Trasforma i caratteri esistenti dopo il caricamento del documento e il completamento della sostituzione dei caratteri. Le trasformazioni dei caratteri possono modificare qualsiasi carattere nel documento, inclusi i caratteri caricati correttamente. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Nascondi markup e tracciamento delle modifiche per i documenti Word. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Imposta le opzioni di sillabazione per i documenti WordProcessing. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Mantieni il valore originale del campo data. Predefinito: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Abilita o disabilita la generazione della numerazione di pagina nel documento convertito. Predefinito: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Determina se la struttura del documento deve essere preservata durante la conversione in PDF (il valore predefinito è false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Specifica se preservare i campi modulo di Microsoft Word come campi modulo nel PDF o convertirli in testo. Il valore predefinito è false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Mostra il nome completo del commentatore nei commenti. Il valore predefinito è false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Aggiorna i campi dopo il caricamento. Predefinito: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Aggiorna il layout della pagina dopo il caricamento. Predefinito: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Specifica se utilizzare un modellatore di testo per una migliore visualizzazione del kerning. Il valore predefinito è false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### Osservazioni

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Gestisce i caratteri mancanti/non disponibili usando FontSubstitutes, DefaultFont e la sostituzione di sistema

• Ordine di elaborazione: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Modifica tutti i caratteri esistenti nel documento caricato usando FontReplacements

• Applicato dopo che tutte le sostituzioni dei caratteri sono completate

### IConversionConvertOptions

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

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
