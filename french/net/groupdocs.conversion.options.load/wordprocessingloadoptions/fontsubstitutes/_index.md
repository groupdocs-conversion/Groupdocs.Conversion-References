---
title: "FontSubstitutes"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Remplace des polices spécifiques lors de la conversion d'un document WordsProcessing."
type: docs
weight: 150
url: /fr/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes/
---
## WordProcessingLoadOptions.FontSubstitutes property

Remplace des polices spécifiques lors de la conversion d'un document WordsProcessing.

```csharp
public IList<FontSubstitute> FontSubstitutes { get; set; }
```

### Remarques

**Note:** The order of substitution is as follows:

1) Remplacer automatiquement les polices manquantes en fonction du nom de la police (si activé).

2) Remplacer automatiquement les polices manquantes en fonction de FontConfig (si activé).

3) Remplacer les polices manquantes en fonction de FontSubstitutes (si défini).

4) Remplacer automatiquement les polices manquantes en fonction de FontInfo (si activé).

5) Remplacer les polices manquantes en fonction de DefaultFont (si défini).

### Voir aussi

* class [FontSubstitute](../../../groupdocs.conversion.contracts/fontsubstitute)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
