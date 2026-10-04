---
title: "PageDescriptionLanguageConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file page descriptions language."
type: docs
weight: 2030
url: /it/net/groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/
---
## PageDescriptionLanguageConvertOptions class

Opzioni per la conversione al tipo di file page descriptions language.

```csharp
public class PageDescriptionLanguageConvertOptions : 
    CommonConvertOptions<PageDescriptionLanguageFileType>
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PageDescriptionLanguageConvertOptions](pagedescriptionlanguageconvertoptions)() | Inizializza una nuova istanza di [`PageDescriptionLanguageConvertOptions`](../pagedescriptionlanguageconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [Height](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/height) { get; set; } | Altezza della pagina desiderata dopo la conversione, in pixel indipendenti dal dispositivo di 1/96 di pollice ciascuno. Lasciare a 0 per consentire al target di mantenere l'altezza della pagina che determina autonomamente. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Width](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/width) { get; set; } | Larghezza della pagina desiderata dopo la conversione, in pixel indipendenti dal dispositivo di 1/96 di pollice ciascuno. Lasciare a 0 per consentire al target di mantenere la larghezza della pagina che determina autonomamente. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PageDescriptionLanguageFileType](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
