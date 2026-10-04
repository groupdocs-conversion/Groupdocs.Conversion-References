---
title: "EmailConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Email."
type: docs
weight: 1800
url: /it/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Opzioni per la conversione al tipo di file Email.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Inizializza una nuova istanza della classe [`EmailConvertOptions`](../emailconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Un delegato per gestire l'elaborazione personalizzata degli allegati email. Il delegato riceve come parametri il nome dell'allegato, il tipo di contenuto e lo stream originale dell'allegato e restituisce lo stream dell'allegato modificato. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
