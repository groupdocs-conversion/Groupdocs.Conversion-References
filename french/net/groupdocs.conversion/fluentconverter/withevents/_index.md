---
title: "WithEvents"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Variante d'étape d'entrée de la chaîne fluide qui commence avec les gestionnaires d'événements du cycle de vie de la conversion. Elle se situe au même stade d'entrée que WithSettingsgroupdocs.conversion/fluentconverter/withsettings et le sac ConversionEventsgroupdocs.conversion/conversionevents résultant se déclenche à chaque exécution de conversion par le convertisseur."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Variante d'étape d'entrée de la chaîne fluide qui commence avec les gestionnaires d'événements du cycle de vie de la conversion. Elle se situe au même stade d'entrée que [`WithSettings`](../withsettings), et le sac [`ConversionEvents`](../../conversionevents) résultant se déclenche à chaque exécution de conversion par le convertisseur.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| configure | Action`1 | Action qui modifie le sac d'événements. |

### Valeur de retour

L'étape de sélection de la source afin que `Load` puisse être enchaînée.

### Voir aussi

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
