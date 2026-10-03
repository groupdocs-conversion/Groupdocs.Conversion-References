---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Étape aplatie des gestionnaires de conversion. Permet de définir OnConversionCompleted ou OnConversionFailed dans n'importe quel ordre et un nombre illimité de fois avant de passer à Convert / Compress. Les événements doivent être enregistrés à l'étape précoce via WithEvents./iconversionsettings/withevents au lieu de cette étape."
type: docs
weight: 1480
url: /fr/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Étape aplatie des gestionnaires de conversion. Permet de définir `OnConversionCompleted` ou `OnConversionFailed` dans n'importe quel ordre et un nombre illimité de fois, avant de passer à `Convert` / `Compress`. Les événements doivent être enregistrés à l'étape précoce via [`WithEvents`](../iconversionsettings/withevents) au lieu de cette étape.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Méthodes

| Nom | Description |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Enregistre un rappel à invoquer lorsqu'une conversion de document se termine avec succès. Un nouvel appel remplace tout gestionnaire précédemment défini. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Enregistre un rappel à invoquer lorsqu'une conversion de document échoue. Un nouvel appel remplace tout gestionnaire précédemment défini. |

### Voir aussi

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
