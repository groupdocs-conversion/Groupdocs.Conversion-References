---
title: OnConversionCompleted
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Recevoir le flux de documents convertis. Ne sera déclenché que si Savestring ou SaveSaveDocumentStreamForFileType est défini.
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Recevoir le flux de documents convertis. Ne sera déclenché que si "Save(string)" ou "Save(SaveDocumentStreamForFileType)" est défini.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    ConvertedDocumentStream convertedDocumentStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| convertedDocumentStream | ConvertedDocumentStream | Fournisseur de flux de documents converti |

### Return_Value

Interface pour continuer la conversion

### Voir également

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* interface [IConversionCompleted](../../iconversioncompleted)
* espace de noms [GroupDocs.Conversion.Fluent](../../iconversioncompleted)
* Assemblée [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->