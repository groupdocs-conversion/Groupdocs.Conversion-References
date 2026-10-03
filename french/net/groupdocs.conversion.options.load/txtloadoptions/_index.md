---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Txt."
type: docs
weight: 2870
url: /fr/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Options de chargement des documents Txt.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Initialise une nouvelle instance de la classe [`TxtLoadOptions`](../txtloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Police à utiliser lors du rendu du contenu texte brut pendant la conversion. Comme les fichiers TXT ne contiennent pas d'informations de police, cette propriété spécifie la police d'affichage pour le contenu texte. Valeur par défaut : Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. La valeur par défaut est true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Obtient ou définit l'encodage qui sera utilisé lors du chargement du document Txt. Peut être null. Valeur par défaut est null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Type de fichier du document d'entrée. Il est `null` jusqu'à ce qu'un format soit défini, donc testez-le pour `null` plutôt que contre [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), ce qui n'est jamais égal. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Obtient ou définit l'option préférée de gestion des espaces en début. La valeur par défaut est [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Obtient ou définit l'option préférée de gestion des espaces en fin. La valeur par défaut est [`Trim`](../txttrailingspacesoptions/trim). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Remarques

**Font Configuration for Plain Text:**

Comme les fichiers TXT ne contiennent pas d'informations de police, utilisez DefaultTextFont pour spécifier

la police pour le rendu du contenu texte brut pendant la conversion.

### Voir aussi

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
