---
title: "WithEvents"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistrez les gestionnaires d'événements du cycle de vie de la conversion sur un sac ConversionEventsgroupdocs.conversion/conversionevents qui vit pendant la durée de vie du convertisseur et se déclenche à chaque exécution de conversion. Peut être appelé avant ou après WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Les appels multiples accumulent le même sac interne qui est passé à chaque action configure, de sorte que les gestionnaires définis lors des appels précédents survivent sauf s'ils sont écrasés par un appel ultérieur."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

Enregistrez les gestionnaires d'événements du cycle de vie de la conversion sur un sac [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) qui vit pendant la durée de vie du convertisseur et se déclenche à chaque exécution de conversion. Peut être appelé avant ou après [`WithSettings`](../../iconversionsettings/withsettings). Les appels multiples accumulent : le même sac interne est passé à chaque action *configure*, de sorte que les gestionnaires définis lors des appels précédents survivent sauf s'ils sont écrasés par un appel ultérieur.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| configure | Action`1 | Action qui modifie le sac d'événements. |

### Valeur de retour

Cette étape afin que les appels ultérieurs d'étape d'entrée ou `Load` puissent être enchaînés.

### Voir aussi

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
