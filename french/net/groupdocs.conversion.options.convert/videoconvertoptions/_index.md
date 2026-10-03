---
title: "VideoConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type Vidéo."
type: docs
weight: 2280
url: /fr/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

Options de conversion vers le type Vidéo.

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | Initialise une nouvelle instance de la classe [`VideoConvertOptions`](../videoconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | Quel format audio doit être utilisé |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | Si défini sur true, extrait l'audio de la vidéo |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | Images par seconde. La valeur par défaut est 30. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
