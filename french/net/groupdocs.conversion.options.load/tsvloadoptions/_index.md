---
title: "TsvLoadOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de chargement des documents Tsv."
type: docs
weight: 2850
url: /fr/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Options de chargement des documents Tsv.

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | Initialise une nouvelle instance de la classe [`TsvLoadOptions`](../tsvloadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Si AllColumnsInOnePagePerSheet est vrai, le contenu de toutes les colonnes d'une feuille sera exporté sur une seule page dans le résultat. La largeur du format de papier du paramètre pagesetup sera invalide, mais les autres paramètres de pagesetup resteront appliqués. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Ajuste automatiquement toutes les lignes lors de la conversion |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Détermine si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules. Par exemple, Excel n'autorise pas la saisie d'une chaîne de caractères supérieure à 32 K. Lorsque vous saisissez une valeur supérieure à 32 K, si cette propriété est vraie, vous obtiendrez une exception. Si cette propriété est fausse, nous accepterons votre chaîne saisie comme valeur de la cellule afin que vous puissiez ensuite exporter la chaîne complète vers d'autres formats de fichier tels que CSV. Cependant, si vous avez défini une valeur de ce type qui n'est pas valide pour le format de fichier Excel, vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, il peut y avoir une erreur inattendue dans le fichier Excel généré. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Supprime les propriétés de métadonnées intégrées du document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Supprime les propriétés de métadonnées personnalisées du document. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Divise une feuille de calcul en pages par colonnes. La valeur par défaut est 0, aucune pagination. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Implémente [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Valeur par défaut : false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Implémente [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Valeur par défaut : true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Convertit une plage spécifique lors de la conversion vers un format autre que le tableur. Exemple : "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Obtient ou définit les informations de culture système au moment du chargement du fichier |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Police par défaut pour le document de tableur. La police suivante sera utilisée si une police est manquante. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Implémente [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Valeur par défaut : 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Remplace des polices spécifiques lors de la conversion du document de tableur. |
| [Format](../../groupdocs.conversion.options.load/tsvloadoptions/format) { get; } | Type de fichier du document d'entrée. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type de fichier du document d'entrée. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Indique s'il faut ignorer les erreurs de calcul de formule. L'erreur peut être une fonction non prise en charge, des liens externes, etc. La valeur par défaut est false. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Paramètres des marges de page |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Si OnePagePerSheet est true, le contenu de la feuille sera converti en une page dans le document PDF. La valeur par défaut est true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Si True et que la conversion est vers PDF, la conversion est optimisée pour une meilleure taille de fichier au détriment de la qualité d'impression. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Définit le mot de passe pour déprotéger le document protégé. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Détermine si la structure du document doit être préservée lors de la conversion en PDF (par défaut, false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Représente la façon dont les commentaires sont imprimés avec la feuille. La valeur par défaut est PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Réinitialise les dossiers de polices avant de charger le document |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Divise une feuille de calcul en pages par lignes. La valeur par défaut est 0, aucune pagination. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Liste des index de feuilles à convertir. Les index doivent être basés sur zéro |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nom de la feuille à convertir |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Afficher les lignes de grille lors de la conversion des fichiers Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Afficher les feuilles masquées lors de la conversion des fichiers Excel. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Paramètres de taille de page |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Ignore les lignes et colonnes vides lors de la conversion. La valeur par défaut est True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Implémente [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Ignorer les pieds de page lors de la conversion des documents de tableur. Valeur par défaut : false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Ignorer les en-têtes lors de la conversion des documents de tableur. Valeur par défaut : false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Implémente [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Clone l'instance actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
