---
title: SpreadsheetLoadOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Options de chargement des documents de feuille de calcul.
type: docs
weight: 2010
url: /fr/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Options de chargement des documents de feuille de calcul.

```csharp
public class SpreadsheetLoadOptions : LoadOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Initialise la nouvelle instance de[`SpreadsheetLoadOptions`](../spreadsheetloadoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Si vérifier la restriction du fichier Excel lorsque l'utilisateur modifie les objets liés aux cellules. Par exemple, Excel n'autorise pas la saisie d'une valeur de chaîne supérieure à 32 Ko. Lorsque vous entrez une valeur supérieure à 32 Ko, si cette propriété est vraie, vous obtiendrez une exception. Si cette propriété est fausse, nous accepterons votre valeur de chaîne d'entrée comme valeur de la cellule afin que vous puissiez ultérieurement générer la valeur de chaîne complète pour d'autres formats de fichier tels que CSV. Toutefois, si vous avez défini un type de valeur non valide pour le format de fichier Excel, vous ne devez pas enregistrer le classeur au format de fichier Excel ultérieurement. Sinon, il peut y avoir une erreur inattendue pour le fichier Excel généré. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Convertir une plage spécifique lors de la conversion en un format autre qu'un tableur. Exemple : "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Obtenir ou définir les informations de culture système au moment où le fichier est chargé |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Police par défaut pour le document de feuille de calcul. La police suivante sera utilisée si une police est manquante. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Remplacez des polices spécifiques lors de la conversion d'un document de feuille de calcul. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Type de fichier du document d'entrée. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Masquer les commentaires. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Si OnePagePerSheet est vrai, le contenu de la feuille sera converti en une page dans le document PDF. La valeur par défaut est true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Si True et conversion en PDF, la conversion est optimisée pour une meilleure taille de fichier que la qualité d'impression. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Définir le mot de passe pour déprotéger le document protégé. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nom de la feuille à convertir |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Afficher les lignes de grille lors de la conversion de fichiers Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Afficher les feuilles masquées lors de la conversion de fichiers Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Ignore les lignes et les colonnes vides lors de la conversion. La valeur par défaut est True. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [LoadOptions](../loadoptions)
* espace de noms [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
