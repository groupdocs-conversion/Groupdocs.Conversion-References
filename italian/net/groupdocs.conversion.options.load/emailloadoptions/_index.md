---
title: "EmailLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Email."
type: docs
weight: 2500
url: /it/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Opzioni per il caricamento di documenti Email.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Inizializza una nuova istanza della classe [`EmailLoadOptions`](../emailloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | Ottiene o imposta l'elenco delle icone degli allegati. L'elenco può essere personalizzato per fornire icone specifiche per diversi tipi di file. Per impostazione predefinita, contiene icone comuni dei tipi di file. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Il valore predefinito è true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Il valore predefinito è true |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | Implementa [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento email. Il carattere seguente verrà utilizzato se un carattere è mancante. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Opzione per visualizzare o nascondere gli allegati nell'intestazione. Predefinito: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Opzione per visualizzare o nascondere l'indirizzo email "Bcc". Predefinito: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Opzione per visualizzare o nascondere l'indirizzo email "Cc". Predefinito: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Opzione per controllare se gli indirizzi email sono visualizzati accanto ai nomi. Esempio: "John Doe &lt;john.doe@sample.com&gt;" o solo "John Doe." Predefinito: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Opzione per visualizzare o nascondere l'indirizzo email "from". Predefinito: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Opzione per visualizzare o nascondere l'intestazione email. Predefinito: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Opzione per visualizzare o nascondere la data/ora di invio nell'intestazione. Predefinito: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Opzione per visualizzare o nascondere l'oggetto nell'intestazione. Predefinito: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Opzione per visualizzare o nascondere l'indirizzo email "to". Predefinito: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | La mappatura tra il messaggio email [`EmailField`](../emailfield) e la rappresentazione testuale del campo |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | Elenco di sostituzioni di caratteri. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | Impostazioni dell'orientamento della pagina |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | Implementa [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Definisce se è necessario mantenere la stringa originale dell'intestazione della data nel messaggio di posta durante il salvataggio o meno (Il valore predefinito è true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Timeout per il caricamento delle risorse esterne |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Ottiene o imposta il compenso dell'ora universale coordinata (UTC) per le date dei messaggi. Questa proprietà definisce la differenza di fuso orario, tra l'ora locale e UTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | Ottiene o imposta se utilizzare le icone predefinite per gli allegati. Predefinito: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
