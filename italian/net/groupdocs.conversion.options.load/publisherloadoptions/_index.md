---
title: "PublisherLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Publisher."
type: docs
weight: 2790
url: /it/net/groupdocs.conversion.options.load/publisherloadoptions/
---
## PublisherLoadOptions class

Opzioni per il caricamento di documenti Publisher.

```csharp
public class PublisherLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PublisherLoadOptions](publisherloadoptions)() | Inizializza una nuova istanza della classe [`PublisherLoadOptions`](../publisherloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/publisherloadoptions/defaultfont) { get; set; } | Font predefinito per il documento Publisher. Il font seguente verrà utilizzato se un font è mancante. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/publisherloadoptions/fontsubstitutes) { get; set; } | Sostituisci font specifici durante la conversione del documento Publisher. |
| [Format](../../groupdocs.conversion.options.load/publisherloadoptions/format) { get; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
