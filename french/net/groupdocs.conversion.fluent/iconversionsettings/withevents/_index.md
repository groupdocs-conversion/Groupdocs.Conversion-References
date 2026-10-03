---
title: "WithEvents"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistrez les gestionnaires d'événements du cycle de vie de la conversion sur un sac ConversionEventsgroupdocs.conversion/conversionevents qui vit pendant la durée de vie du convertisseur et se déclenche à chaque exécution de conversion. Il se situe au même stade d'entrée que WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Les appels multiples s'accumulent : le même sac interne est passé à chaque action configure, de sorte que les gestionnaires définis lors des appels précédents survivent sauf s'ils sont remplacés par un appel ultérieur."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Enregistrez les gestionnaires d'événements du cycle de vie de la conversion sur un sac [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) qui vit pendant la durée de vie du convertisseur et se déclenche à chaque exécution de conversion. Il se situe au même stade d'entrée que [`WithSettings`](../withsettings). Les appels multiples s'accumulent : le même sac interne est passé à chaque action *configure*, de sorte que les gestionnaires définis lors des appels précédents survivent sauf s'ils sont remplacés par un appel ultérieur.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| configure | Action`1 | Action qui modifie le sac d'événements. |

### Valeur de retour

L'étape de sélection de la source afin que `Load` puisse être enchaînée.

### Voir aussi

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
