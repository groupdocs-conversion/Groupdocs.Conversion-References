---
title: "WithOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les options de conversion pour le processus de conversion."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Définit les options de conversion pour le processus de conversion.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptions | ConvertOptions | Options de conversion. |

### Valeur de retour

Étape des gestionnaires pour poursuivre la construction de la conversion.

### Voir aussi

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Définit les options de conversion en utilisant une fonction fournisseur.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| optionsProvider | Func`2 | Une fonction qui fournit des options de conversion en fonction du contexte de conversion. |

### Valeur de retour

Étape des gestionnaires pour poursuivre la construction de la conversion.

### Voir aussi

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
