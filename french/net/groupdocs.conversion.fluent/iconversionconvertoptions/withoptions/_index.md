---
title: "WithOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définir les options de conversion"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Définir les options de conversion

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptions | ConvertOptions | Options de conversion |

### Valeur de retour

Interface pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Définir les options de conversion

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Description |
| --- | --- |
| convertOptionsProvider | Fournisseur d'options de conversion |
| convertOptionsProvider arg1arg1 | Le [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Valeur de retour

Interface pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
