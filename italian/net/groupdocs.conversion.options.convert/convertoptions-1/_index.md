---
title: "ConvertOptionsTFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Classe astratta generica per le opzioni di conversione."
type: docs
weight: 1770
url: /it/net/groupdocs.conversion.options.convert/convertoptions-1/
---
## ConvertOptions&lt;TFileType&gt; class

Classe astratta generica per le opzioni di conversione.

```csharp
public abstract class ConvertOptions<TFileType> : ConvertOptions
    where TFileType : FileType
```

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
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

* class [ConvertOptions](../convertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
