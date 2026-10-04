---
title: "DefaultFont"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stelt het standaardlettertype in voor een WordProcessing-document."
type: docs
weight: 90
url: /nl/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Stelt het standaardlettertype in voor een WordProcessing-document.

```csharp
public string DefaultFont { get; set; }
```

### Opmerkingen

**Note:** The order of substitution is as follows:

1) Vervang automatisch ontbrekende lettertypen op basis van de lettertype‑naam (indien ingeschakeld).

2) Vervang automatisch ontbrekende lettertypen op basis van FontConfig (indien ingeschakeld).

3) Vervang ontbrekende lettertypen op basis van FontSubstitutes (indien ingesteld).

4) Vervang automatisch ontbrekende lettertypen op basis van FontInfo (indien ingeschakeld).

5) Vervang ontbrekende lettertypen op basis van DefaultFont (indien ingesteld).

### Zie ook

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
