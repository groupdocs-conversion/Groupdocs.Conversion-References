---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier Feuille de calcul."
type: docs
weight: 2240
url: /fr/net/groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
## SpreadsheetConvertOptions class

Options de conversion vers le type de fichier Feuille de calcul.

```csharp
public class SpreadsheetConvertOptions : CommonConvertOptions<SpreadsheetFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetConvertOptions](spreadsheetconvertoptions)() | Initialise une nouvelle instance de la classe [`SpreadsheetConvertOptions`](../spreadsheetconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/encoding) { get; set; } | Spécifie l'encodage à utiliser lors de la conversion vers des formats délimités. |
| [Format](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. (2 propriétés) |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implémente [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implémente [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implémente [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/password) { get; set; } | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
| [Separator](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/separator) { get; set; } | Spécifie le séparateur à utiliser lors de la conversion vers des formats délimités. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implémente [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/zoom) { get; set; } | Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [SpreadsheetFileType](../../groupdocs.conversion.filetypes/spreadsheetfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
