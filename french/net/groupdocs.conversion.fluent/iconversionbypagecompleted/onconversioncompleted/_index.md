---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Recevoir le flux de page converti. Ne sera déclenché que si ConvertToconvertedStreamProvider est défini."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Recevoir le flux de page converti. Ne sera déclenché que si "ConvertTo(convertedStreamProvider)" est défini.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertedPageStream | Action`1 | Fournisseur de flux de page converti Le [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Valeur de retour

Interface pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
