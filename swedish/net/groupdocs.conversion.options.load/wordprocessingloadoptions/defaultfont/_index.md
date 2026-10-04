---
title: "DefaultFont"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ställer in standardteckensnittet för ett WordProcessing‑dokument."
type: docs
weight: 90
url: /sv/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Ställer in standardteckensnittet för ett WordProcessing‑dokument.

```csharp
public string DefaultFont { get; set; }
```

### Anmärkningar

**Note:** The order of substitution is as follows:

1) Byt automatiskt ut saknade teckensnitt baserat på teckensnittsnamn (om aktiverat).

2) Byt automatiskt ut saknade teckensnitt baserat på FontConfig (om aktiverat).

3) Ersätt saknade teckensnitt baserat på FontSubstitutes (om angivet).

4) Byt automatiskt ut saknade teckensnitt baserat på FontInfo (om aktiverat).

5) Ersätt saknade teckensnitt baserat på DefaultFont (om angivet).

### Se även

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
