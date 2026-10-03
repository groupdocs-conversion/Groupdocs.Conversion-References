---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistre un rappel à invoquer lorsqu'une conversion de document échoue. Réinvoquer remplace tout gestionnaire précédemment défini."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Enregistre un rappel à invoquer lorsqu'une conversion de document échoue. Un nouvel appel remplace tout gestionnaire précédemment défini.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| onFailed | Action`2 | Une action pour gérer l'échec, recevant le contexte de conversion et l'exception qui a causé l'échec. |

### Valeur de retour

Cette étape, ainsi des gestionnaires supplémentaires ou `Convert` / `Compress` peuvent être enchaînés.

### Voir aussi

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
