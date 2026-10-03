---
title: "FontTransformations"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Transforme les polices existantes après le chargement du document et la substitution de polices sont terminées. Les transformations de polices peuvent modifier toutes les polices du document, y compris les polices qui ont été chargées avec succès."
type: docs
weight: 160
url: /fr/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations/
---
## WordProcessingLoadOptions.FontTransformations property

Transforme les polices existantes après le chargement du document et la substitution des polices. Les transformations de polices peuvent modifier toutes les polices du document, y compris celles qui ont été chargées avec succès.

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### Remarques

**Note:** Font transformations are applied after all font substitution steps are complete.

Les transformations sont traitées dans l'ordre où elles apparaissent dans la liste.

Cas d'utilisation : modifications de style, exigences de marque, améliorations d'accessibilité.

### Voir aussi

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
