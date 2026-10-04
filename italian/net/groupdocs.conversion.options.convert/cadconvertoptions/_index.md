---
title: "CadConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo Cad."
type: docs
weight: 1730
url: /it/net/groupdocs.conversion.options.convert/cadconvertoptions/
---
## CadConvertOptions class

Opzioni per la conversione al tipo Cad.

```csharp
public class CadConvertOptions : ConvertOptions<CadFileType>, IPagedConvertOptions, IPageSizeOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CadConvertOptions](cadconvertoptions)() | Inizializza una nuova istanza della classe [`CadConvertOptions`](../cadconvertoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/cadconvertoptions/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PagesCount](../../groupdocs.conversion.options.convert/cadconvertoptions/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/cadconvertoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza corrente delle opzioni. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CadFileType](../../groupdocs.conversion.filetypes/cadfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
