---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistre un rappel à invoquer lorsqu'une conversion de document se termine avec succès. Réinvoquer remplace tout gestionnaire précédemment défini."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Enregistre un rappel à invoquer lorsqu'une conversion de document se termine avec succès. Un nouvel appel remplace tout gestionnaire précédemment défini.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| onCompleted | Action`1 | Une action pour gérer l'achèvement, recevant le contexte de conversion. |

### Valeur de retour

Cette étape, ainsi des gestionnaires supplémentaires ou `Convert` / `Compress` peuvent être enchaînés.

### Voir aussi

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
