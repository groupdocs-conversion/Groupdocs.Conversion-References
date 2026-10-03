---
title: "VideoLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents vidéo."
type: docs
weight: 2910
url: /fr/net/groupdocs.conversion.options.load/videoloadoptions/
---
## VideoLoadOptions class

Options de chargement des documents vidéo.

```csharp
public sealed class VideoLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VideoLoadOptions](videoloadoptions)() | Initialise une nouvelle instance de la classe [`VideoLoadOptions`](../videoloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/videoloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/videoloadoptions/setvideoconnector)(IVideoConnector) | Définir le connecteur du document vidéo |

### Voir aussi

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
