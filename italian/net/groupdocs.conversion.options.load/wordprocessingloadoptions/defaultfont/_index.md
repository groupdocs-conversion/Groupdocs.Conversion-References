---
title: "DefaultFont"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Imposta il carattere predefinito per un documento WordProcessing."
type: docs
weight: 90
url: /it/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Imposta il carattere predefinito per un documento WordProcessing.

```csharp
public string DefaultFont { get; set; }
```

### Osservazioni

**Note:** The order of substitution is as follows:

1) Sostituisci automaticamente i caratteri mancanti in base al nome del carattere (se abilitato).

2) Sostituisci automaticamente i caratteri mancanti in base a FontConfig (se abilitato).

3) Sostituisci i caratteri mancanti in base a FontSubstitutes (se impostato).

4) Sostituisci automaticamente i caratteri mancanti in base a FontInfo (se abilitato).

5) Sostituisci i caratteri mancanti in base a DefaultFont (se impostato).

### IConversionConvertOptions

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
