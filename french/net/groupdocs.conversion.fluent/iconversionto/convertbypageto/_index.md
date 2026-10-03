---
title: "ConvertByPageTo"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Enregistrer la page convertie en flux"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionto/convertbypageto/
---
## IConversionTo.ConvertByPageTo method

Enregistrer la page convertie en flux

```csharp
public IConversionByPageOptionsOrHandlerSetup ConvertByPageTo(
    Func<SavePageContext, Stream> convertedStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Fournisseur de flux de page de document converti Le contexte d'enregistrement |

### Valeur de retour

Options de page ou interface de configuration du gestionnaire pour poursuivre la construction de la conversion

### Voir aussi

* interface [IConversionByPageOptionsOrHandlerSetup](../../iconversionbypageoptionsorhandlersetup)
* class [SavePageContext](../../../groupdocs.conversion/savepagecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
