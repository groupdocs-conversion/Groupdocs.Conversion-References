---
title: "CadLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti CAD."
type: docs
weight: 2430
url: /it/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Opzioni per il caricamento di documenti CAD.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Inizializza una nuova istanza della classe [`CadLoadOptions`](../cadloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Ottiene o imposta un colore di sfondo. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Ottiene o imposta le sorgenti CTB. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Ottiene o imposta il colore di primo piano. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Ottiene o imposta il tipo di disegno. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Specifica quali layout CAD devono essere convertiti |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Ottiene o imposta quali spazi di disegno vengono convertiti. Il valore predefinito è [`Both`](../cadlayoutscope/both), che non limita la conversione. Viene ignorato quando viene fornito [`LayoutNames`](./layoutnames), poiché i nomi di layout espliciti hanno sempre la precedenza. Un valore `null` è trattato come [`Both`](../cadlayoutscope/both). |

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
