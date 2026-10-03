---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Arguments transmis à ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /fr/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Arguments transmis à [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Nom de fichier (ou identifiant de substitut) intégré en tant qu’URI de l’image dans la sortie Markdown. Attribuez‑le pour réécrire l’URI. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Flux de destination dans lequel le convertisseur écrira les octets de l’image après le retour de ce rappel. Remplacez‑le par votre propre flux accessible en écriture (par ex. un FileStream pour la persistance sur disque ou un MemoryStream que vous prévoyez de lire ensuite). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Lorsque false (par défaut), le convertisseur ferme [`ImageStream`](./imagestream) après l’écriture — ce qui est habituel pour les remplacements de FileStream qui doivent être vidés sur le disque. Mettez à true pour garder le flux ouvert après la fin de la conversion (typique pour un MemoryStream que vous prévoyez de lire vous‑même) ; l’appelant en devient alors responsable de la libération. |

### Voir aussi

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
