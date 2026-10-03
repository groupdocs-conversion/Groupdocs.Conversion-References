---
title: "LayoutScope"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Obtient ou définit les espaces de dessin qui sont convertis. La valeur par défaut est Bothgroupdocs.conversion.options.load/cadlayoutscope/both qui ne restreint pas la conversion. Elle est ignorée lorsque LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames est fourni car les noms de mise en page explicites l’emportent toujours. Une valeur null est traitée comme Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /fr/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Obtient ou définit les espaces de dessin qui sont convertis. La valeur par défaut est [`Both`](../../cadlayoutscope/both), qui ne restreint pas la conversion. Elle est ignorée lorsque [`LayoutNames`](../layoutnames) est fourni, car les noms de mise en page explicites l’emportent toujours. Une valeur `null` est traitée comme [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Remarques

Un périmètre qui ne sélectionne aucune des feuilles proposées par un dessin entraîne l’échec de la conversion avec une [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) indiquant le périmètre et les feuilles présentes, plutôt que de rendre les espaces exclus par le périmètre. Un dessin qui ne propose aucune feuille n’est pas affecté et se convertit toujours en une seule unité. Non respecté lors de la conversion vers PDF/UA-1, pour la raison indiquée dans [`LayoutNames`](../layoutnames).

### Voir aussi

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
