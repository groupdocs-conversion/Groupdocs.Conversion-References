---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents Spreadsheet. Inclut les types de fichiers suivants Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. En savoir plus sur les formats Spreadsheet icihttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /fr/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Définit les documents Spreadsheet. Inclut les types de fichiers suivants : [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). En savoir plus sur les formats Spreadsheet [ici](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Les fichiers avec l'extension CSV (Comma Separated Values) représentent des fichiers texte brut qui contiennent des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF signifie Data Interchange Format, qui est utilisé pour importer/exporter des données de feuilles de calcul entre différentes applications. Celles-ci incluent Microsoft Excel, OpenOffice Calc, StarCalc et bien d'autres. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel est un Office Open XML SpreadsheetML stocké dans un fichier XML plat au lieu d'un package ZIP. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Un fichier avec l'extension .fods est un type de format de document OpenDocument Spreadsheet qui stocke les données en lignes et colonnes. Le format est spécifié dans le cadre des spécifications ODF 1.2 publiées et maintenues par OASIS. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Les fichiers avec l'extension .numbers sont classés comme type de fichier feuille de calcul, c'est pourquoi ils sont similaires aux fichiers .xlsx ; mais les fichiers Numbers sont créés en utilisant le logiciel de feuille de calcul Apple iWork Numbers. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Les fichiers avec l'extension ODS désignent le format de document OpenDocument Spreadsheet qui est éditable par l'utilisateur. Les données sont stockées dans le fichier ODF sous forme de lignes et colonnes. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Un fichier avec l'extension .ots est un modèle de feuille de calcul OpenDocument Spreadsheet créé avec le logiciel d'application Calc inclus dans Apache OpenOffice. Le logiciel d'application Calc est similaire à Excel disponible dans Microsoft Office. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Le format de fichier SXC (Sun XML Calc) appartient à une suite bureautique appelée OpenOffice.org. Ce format répond généralement aux besoins de feuilles de calcul des utilisateurs car il s'agit d'un format de fichier feuille de calcul basé sur XML. Le format SXC prend en charge les formules, fonctions, macros et graphiques ainsi que DataPilot. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Un format de fichier Tab-Separated Values (TSV) représente des données séparées par des tabulations dans un format texte brut. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM est un fichier Macro-Enabled Add-In qui est utilisé pour ajouter de nouvelles fonctions aux feuilles de calcul. Un Add-In est un programme supplémentaire qui exécute du code additionnel et fournit des fonctionnalités supplémentaires aux feuilles de calcul. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS représente le format de fichier Excel Binary File Format. De tels fichiers peuvent être créés par Microsoft Excel ainsi que par d’autres programmes de tableur similaires tels qu’OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Le format de fichier XLSB spécifie le Excel Binary File Format, qui est une collection d’enregistrements et de structures définissant le contenu d’un classeur Excel. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM est un type de fichiers de feuille de calcul qui prend en charge les macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Les fichiers avec l’extension .XLT sont des fichiers modèle créés avec Microsoft Excel, qui est une application de feuille de calcul faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | L’extension de fichier XLTM représente les fichiers générés par Microsoft Excel en tant que modèles macro‑activés. Les fichiers XLTM sont similaires aux XLTX sur le plan de la structure, à la différence que ce dernier ne prend pas en charge la création de modèles avec macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Le fichier XLTX représente le modèle Microsoft Excel basé sur les spécifications du format de fichier Office OpenXML. Il est utilisé pour créer un fichier modèle standard qui peut être utilisé pour générer des fichiers XLSX présentant les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xltx). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
