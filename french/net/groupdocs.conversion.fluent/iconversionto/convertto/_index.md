---
title: "ConvertTo"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistrer le document converti en fichier"
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Enregistrer le document converti en fichier

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Document converti |

### Valeur de retour

Options ou interface de configuration du gestionnaire pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Enregistrer le document converti en flux

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Fournisseur de flux de document converti Le contexte d'enregistrement |

### Valeur de retour

Options ou interface de configuration du gestionnaire pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
