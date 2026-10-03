---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Étape aplatie des gestionnaires de conversion bypage. Miroir perpage de IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /fr/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Étape aplatie des gestionnaires de conversion par page. Miroir par page de [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Méthodes

| Nom | Description |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Enregistre un rappel à invoquer lorsqu'une conversion de page se termine avec succès. Un nouvel appel remplace tout gestionnaire précédemment défini. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Enregistre un rappel à invoquer lorsqu'une conversion de page échoue. Un nouvel appel remplace tout gestionnaire précédemment défini. |

### Voir aussi

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
