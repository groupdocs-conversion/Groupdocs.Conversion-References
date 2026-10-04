---
title: "TxtLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Txt."
type: docs
weight: 2870
url: /it/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Opzioni per il caricamento di documenti Txt.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Inizializza una nuova istanza della classe [`TxtLoadOptions`](../txtloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Carattere da utilizzare durante il rendering del contenuto di testo semplice durante la conversione. Poiché i file TXT non contengono informazioni sul carattere, questa proprietà specifica il carattere di visualizzazione per il contenuto testuale. Predefinito: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Consente di specificare come vengono riconosciuti gli elementi delle liste numerate quando il documento di testo semplice viene convertito. Il valore predefinito è true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Ottiene o imposta la codifica che verrà utilizzata durante il caricamento del documento Txt. Può essere null. Il valore predefinito è null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. Il valore predefinito è [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. Il valore predefinito è [`Trim`](../txttrailingspacesoptions/trim). |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### Osservazioni

**Font Configuration for Plain Text:**

Poiché i file TXT non contengono informazioni sul carattere, utilizzare DefaultTextFont per specificare

il carattere per il rendering del contenuto di testo semplice durante la conversione.

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
