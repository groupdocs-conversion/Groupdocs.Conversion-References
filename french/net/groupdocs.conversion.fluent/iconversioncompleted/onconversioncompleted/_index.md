---
title: OnConversionCompleted
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Recevoir le flux de documents convertis. Ne sera déclenché que si ConvertTostring fileName ou ConvertToconvertedStreamProvider est défini.
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Recevoir le flux de documents convertis. Ne sera déclenché que si "ConvertTo(string fileName)" ou ConvertTo(convertedStreamProvider)" est défini.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<Stream, string> convertedFileStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| convertedFileStream | Action`2 | Fournisseur de flux de documents converti |

### Return_Value

Interface pour continuer la conversion

### Voir également

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* interface [IConversionCompleted](../../iconversioncompleted)
* espace de noms [GroupDocs.Conversion.Fluent](../../iconversioncompleted)
* Assemblée [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
