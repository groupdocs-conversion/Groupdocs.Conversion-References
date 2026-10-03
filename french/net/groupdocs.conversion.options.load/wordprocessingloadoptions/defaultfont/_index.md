---
title: "DefaultFont"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit la police par défaut pour un document WordProcessing."
type: docs
weight: 90
url: /fr/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Définit la police par défaut pour un document WordProcessing.

```csharp
public string DefaultFont { get; set; }
```

### Remarques

**Note:** The order of substitution is as follows:

1) Remplacer automatiquement les polices manquantes en fonction du nom de la police (si activé).

2) Remplacer automatiquement les polices manquantes en fonction de FontConfig (si activé).

3) Remplacer les polices manquantes en fonction de FontSubstitutes (si défini).

4) Remplacer automatiquement les polices manquantes en fonction de FontInfo (si activé).

5) Remplacer les polices manquantes en fonction de DefaultFont (si défini).

### Voir aussi

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
