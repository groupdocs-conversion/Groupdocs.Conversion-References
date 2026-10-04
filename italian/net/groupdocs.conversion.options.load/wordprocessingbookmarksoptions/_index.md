---
title: "WordProcessingBookmarksOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la gestione dei segnalibri in WordProcessing"
type: docs
weight: 2930
url: /it/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

Opzioni per la gestione dei segnalibri in WordProcessing

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | Il costruttore predefinito. |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | Specifica il livello predefinito nella struttura del documento in cui visualizzare i segnalibri Word. Il valore predefinito è 0. L'intervallo valido è da 0 a 9. |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | Specifica quanti livelli nella struttura del documento mostrare espansi quando il file è visualizzato. Il valore predefinito è 0. L'intervallo valido è da 0 a 9. Nota che questa opzione non funzionerà durante il salvataggio in XPS. |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | Specifica quanti livelli di intestazioni (paragrafi formattati con gli stili Intestazione) includere nella struttura del documento. Il valore predefinito è 0. L'intervallo valido è da 0 a 9. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
