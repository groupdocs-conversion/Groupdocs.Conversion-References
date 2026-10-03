---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistre un rappel à invoquer lorsqu'une conversion de page échoue. Réinvoquer remplace tout gestionnaire précédemment défini."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Enregistre un rappel à invoquer lorsqu'une conversion de page échoue. Un nouvel appel remplace tout gestionnaire précédemment défini.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| onFailed | Action`2 | Une action pour gérer l'échec, recevant le contexte de la page convertie et l'exception qui a causé l'échec. |

### Valeur de retour

Cette étape, ainsi des gestionnaires supplémentaires ou `Convert` / `Compress` peuvent être enchaînés.

### Voir aussi

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
