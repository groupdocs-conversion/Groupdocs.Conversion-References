---
title: "FontSubstitutes"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Sostituisce caratteri specifici durante la conversione di un documento WordsProcessing."
type: docs
weight: 150
url: /it/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes/
---
## WordProcessingLoadOptions.FontSubstitutes property

Sostituisce caratteri specifici durante la conversione di un documento WordsProcessing.

```csharp
public IList<FontSubstitute> FontSubstitutes { get; set; }
```

### Osservazioni

**Note:** The order of substitution is as follows:

1) Sostituisci automaticamente i caratteri mancanti in base al nome del carattere (se abilitato).

2) Sostituisci automaticamente i caratteri mancanti in base a FontConfig (se abilitato).

3) Sostituisci i caratteri mancanti in base a FontSubstitutes (se impostato).

4) Sostituisci automaticamente i caratteri mancanti in base a FontInfo (se abilitato).

5) Sostituisci i caratteri mancanti in base a DefaultFont (se impostato).

### IConversionConvertOptions

* class [FontSubstitute](../../../groupdocs.conversion.contracts/fontsubstitute)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
