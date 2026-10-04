---
title: "NoteLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti One."
type: docs
weight: 2680
url: /it/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Opzioni per il caricamento di documenti One.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Inizializza una nuova istanza della classe [`NoteLoadOptions`](../noteloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento Note. Il carattere seguente verrà utilizzato se un carattere è mancante. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Sostituisce caratteri specifici durante la conversione del documento Note. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Imposta la password per rimuovere la protezione del documento protetto. |

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
