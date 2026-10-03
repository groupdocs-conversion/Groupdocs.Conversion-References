---
title: "Compress"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Appelez cette méthode pour compresser les résultats de la conversion. Enregistrez un gestionnaire compressedstream à l'étape d'entrée via WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents avec le paramètre OnCompressionCompleted."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

Appelez cette méthode pour compresser les résultats de la conversion. Enregistrez un gestionnaire compressed-stream à l'étape d'entrée via [`WithEvents`](../../iconversionsettings/withevents) (paramètre `OnCompressionCompleted`).

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | CompressionConvertOptions | Options de conversion de compression |

### Valeur de retour

Continuation qui poursuit vers `Convert`.

### Voir aussi

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
