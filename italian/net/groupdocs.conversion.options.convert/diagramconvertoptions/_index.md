---
title: "DiagramConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Diagram."
type: docs
weight: 1780
url: /it/net/groupdocs.conversion.options.convert/diagramconvertoptions/
---
## DiagramConvertOptions class

Opzioni per la conversione al tipo di file Diagram.

```csharp
public sealed class DiagramConvertOptions : CommonConvertOptions<DiagramFileType>
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DiagramConvertOptions](diagramconvertoptions)() | Inizializza una nuova istanza della classe [`DiagramConvertOptions`](../diagramconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AutoFitPageToDrawingContent](../../groupdocs.conversion.options.convert/diagramconvertoptions/autofitpagetodrawingcontent) { get; set; } | Definisce se è necessario ingrandire la pagina per adattare il contenuto del disegno o meno |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [DiagramFileType](../../groupdocs.conversion.filetypes/diagramfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
