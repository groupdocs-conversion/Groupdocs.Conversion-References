---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents One."
type: docs
weight: 2680
url: /fr/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Options de chargement des documents One.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Initialise une nouvelle instance de la classe [`NoteLoadOptions`](../noteloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Police par défaut pour le document Note. La police suivante sera utilisée si une police est manquante. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Remplace les polices spécifiques lors de la conversion du document Note. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Définit le mot de passe pour déprotéger le document protégé. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
