---
title: "AudioLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents audio."
type: docs
weight: 2390
url: /fr/net/groupdocs.conversion.options.load/audioloadoptions/
---
## AudioLoadOptions class

Options de chargement des documents audio.

```csharp
public sealed class AudioLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AudioLoadOptions](audioloadoptions)() | Initialise une nouvelle instance de la classe [`AudioLoadOptions`](../audioloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/audioloadoptions/format) { get; set; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |
| [SetAudioConnector](../../groupdocs.conversion.options.load/audioloadoptions/setaudioconnector)(IAudioConnector) | Définir le connecteur du document audio |

### Voir aussi

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
