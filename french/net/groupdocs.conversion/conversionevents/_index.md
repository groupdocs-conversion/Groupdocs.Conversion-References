---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Regroupe les gestionnaires d'événements du cycle de vie de la conversion. Passez une instance au paramètre events des constructeurs Converter./converter ou à la méthode fluide WithEvents. Préférez cela aux propriétés de gestionnaire individuelles de ConverterSettings./convertersettings qui sont obsolètes."
type: docs
weight: 850
url: /fr/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Regroupe les gestionnaires d'événements du cycle de vie de la conversion. Passez une instance au paramètre `events` du constructeur [`Converter`](../converter) ou à la méthode fluide `WithEvents`. Préférez cela aux propriétés de gestionnaire individuelles de [`ConverterSettings`](../convertersettings), qui sont obsolètes.

```csharp
public sealed class ConversionEvents
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ConversionEvents](conversionevents)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Déclenché lorsque la compression de la sortie de conversion est terminée. Invoqué uniquement dans les builds incluant le pipeline de compression (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Déclenché une fois lorsque l'exécution de la conversion se termine, quel que soit le succès ou l'échec. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Déclenché périodiquement avec la progression de la conversion en pourcentage (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Déclenché une fois au début de l'exécution de la conversion, avant que tout document ne soit traité. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Déclenché une fois par conversion de document complet qui se termine avec succès. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Déclenché une fois par conversion de document complet qui échoue. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Déclenché lorsqu'une police référencée par le document source n'est pas disponible et est substituée (soit par une règle [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute) fournie par le client, soit par la police par défaut configurée, soit par le mécanisme de secours interne du pipeline de conversion). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Déclenché une fois par page lorsqu'une conversion page par page se termine avec succès. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Déclenché une fois par page lorsqu'une conversion page par page échoue. |

### Voir aussi

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
