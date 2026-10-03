---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Configurez les paramètres ou les événements de conversion à l'étape d'entrée avant Load."
type: docs
weight: 1540
url: /fr/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Configurer les paramètres de conversion ou les événements à l'étape d'entrée (avant `Load`).

```csharp
public interface IConversionSettings
```

## Méthodes

| Nom | Description |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Enregistrez les gestionnaires d'événements du cycle de vie de la conversion sur un sac [`ConversionEvents`](../../groupdocs.conversion/conversionevents) qui vit pendant toute la durée de vie du convertisseur et se déclenche à chaque exécution de conversion. Il se situe à la même étape d'entrée que [`WithSettings`](./withsettings). Les appels multiples s'accumulent : le même sac interne est passé à chaque action *configure*, de sorte que les gestionnaires définis lors des appels précédents survivent sauf s'ils sont remplacés par un appel ultérieur. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Définir les paramètres du convertisseur |

### Voir aussi

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
