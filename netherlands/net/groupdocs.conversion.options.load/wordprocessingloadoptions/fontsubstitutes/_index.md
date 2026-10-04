---
title: "FontSubstitutes"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Vervangt specifieke lettertypen bij het converteren van een WordsProcessing-document."
type: docs
weight: 150
url: /nl/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes/
---
## WordProcessingLoadOptions.FontSubstitutes property

Vervangt specifieke lettertypen bij het converteren van een WordsProcessing-document.

```csharp
public IList<FontSubstitute> FontSubstitutes { get; set; }
```

### Opmerkingen

**Note:** The order of substitution is as follows:

1) Vervang automatisch ontbrekende lettertypen op basis van de lettertype‑naam (indien ingeschakeld).

2) Vervang automatisch ontbrekende lettertypen op basis van FontConfig (indien ingeschakeld).

3) Vervang ontbrekende lettertypen op basis van FontSubstitutes (indien ingesteld).

4) Vervang automatisch ontbrekende lettertypen op basis van FontInfo (indien ingeschakeld).

5) Vervang ontbrekende lettertypen op basis van DefaultFont (indien ingesteld).

### Zie ook

* class [FontSubstitute](../../../groupdocs.conversion.contracts/fontsubstitute)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
