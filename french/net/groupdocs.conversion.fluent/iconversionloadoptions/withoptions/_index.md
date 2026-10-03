---
title: "WithOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définir les options de chargement"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

Définir les options de chargement

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| loadOptions | LoadOptions | Options de chargement |

### Voir aussi

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

Fournir les options de chargement pour le document en cours de chargement

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | Fournisseur d'options de chargement Le contexte des options de chargement |

### Voir aussi

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
