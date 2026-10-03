---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistre un rappel à invoquer lorsqu'une conversion de page se termine avec succès. Réinvoquer remplace tout gestionnaire précédemment défini."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Enregistre un rappel à invoquer lorsqu'une conversion de page se termine avec succès. Un nouvel appel remplace tout gestionnaire précédemment défini.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| onCompleted | Action`1 | Une action pour gérer la finalisation, recevant le contexte de la page convertie. |

### Valeur de retour

Cette étape, ainsi des gestionnaires supplémentaires ou `Convert` / `Compress` peuvent être enchaînés.

### Voir aussi

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
