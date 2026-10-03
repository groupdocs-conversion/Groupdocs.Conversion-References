---
title: "KeepImageStreamOpen"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Lorsque la valeur est false (défaut), le convertisseur ferme ImageStreamgroupdocs.conversion.options.convert/markdownimagesavingargs/imagestream après l'écriture, ce qui est idiomatique pour les remplacements de FileStream qui doivent être vidés sur le disque. Réglez sur true pour garder le flux ouvert après la fin de la conversion, typique pour un MemoryStream que vous avez l'intention de lire vous‑même ; l’appelant en devient alors responsable de la libération."
type: docs
weight: 30
url: /fr/net/groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen/
---
## MarkdownImageSavingArgs.KeepImageStreamOpen property

Lorsque la valeur est false (défaut), le convertisseur ferme [`ImageStream`](../imagestream) après l'écriture — ce qui est idiomatique pour les remplacements de FileStream qui doivent être vidés sur le disque. Réglez sur true pour garder le flux ouvert après la fin de la conversion (typique pour un MemoryStream que vous avez l'intention de lire vous‑même) ; l’appelant en devient alors responsable de la libération.

```csharp
public bool KeepImageStreamOpen { get; set; }
```

### Voir aussi

* class [MarkdownImageSavingArgs](../../markdownimagesavingargs)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
