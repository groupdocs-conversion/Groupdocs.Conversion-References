---
title: "WithOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définir les options de conversion"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Définir les options de conversion

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptions | ConvertOptions | Options de conversion |

### Valeur de retour

Interface pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Définir les options de conversion

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Options de conversion Le [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Valeur de retour

Interface pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
