---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Reçoit le flux du document converti. Ne sera déclenché que si ConvertTostring fileName ou ConvertToconvertedStreamProvider est défini."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Reçoit le flux du document converti. Ne sera déclenché que si "ConvertTo(string fileName)" ou ConvertTo(convertedStreamProvider)" est défini.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertedFileStream | Action`1 | Fournisseur de flux de document converti Le [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Valeur de retour

Interface pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
