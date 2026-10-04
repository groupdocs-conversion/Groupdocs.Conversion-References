---
title: "DiagramLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Diagram."
type: docs
weight: 2470
url: /it/net/groupdocs.conversion.options.load/diagramloadoptions/
---
## DiagramLoadOptions class

Opzioni per il caricamento di documenti Diagram.

```csharp
public sealed class DiagramLoadOptions : LoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DiagramLoadOptions](diagramloadoptions)() | Inizializza una nuova istanza della classe [`DiagramLoadOptions`](../diagramloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/diagramloadoptions/defaultfont) { get; set; } | Carattere predefinito per il documento Diagram. Il carattere seguente verrà usato se un carattere è mancante. |
| [Format](../../groupdocs.conversion.options.load/diagramloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
