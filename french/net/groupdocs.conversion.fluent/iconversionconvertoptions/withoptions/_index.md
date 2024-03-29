---
title: WithOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définir les options de conversion
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Définir les options de conversion

```csharp
public IConversionCompletedOrConvert WithOptions(ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| convertOptions | ConvertOptions | Options de conversion |

### Return_Value

Interface pour continuer la conversion

### Voir également

* interface [IConversionCompletedOrConvert](../../iconversioncompletedorconvert)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* espace de noms [GroupDocs.Conversion.Fluent](../../iconversionconvertoptions)
* Assemblée [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;string, FileType, ConvertOptions&gt;) {#withoptions_1}

Définir les options de conversion

```csharp
public IConversionCompletedOrConvert WithOptions(
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | La description |
| --- | --- |
| convertOptionsProvider | Convertir le fournisseur d'options |
| convertOptionsProvider arg2arg2 | Le type du fichier source |

### Return_Value

Interface pour continuer la conversion

### Voir également

* interface [IConversionCompletedOrConvert](../../iconversioncompletedorconvert)
* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* espace de noms [GroupDocs.Conversion.Fluent](../../iconversionconvertoptions)
* Assemblée [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
