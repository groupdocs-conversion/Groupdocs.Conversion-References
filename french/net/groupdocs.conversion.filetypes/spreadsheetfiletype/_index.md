---
title: SpreadsheetFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les documents de feuille de calcul. Inclut les types de fichiers suivants  Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . En savoir plus sur les formats de feuille de calculicihttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 930
url: /fr/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Définit les documents de feuille de calcul. Inclut les types de fichiers suivants : [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . En savoir plus sur les formats de feuille de calcul[ici](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | La description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension de fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | La description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sert de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Les fichiers avec l'extension CSV (Comma Separated Values) représentent des fichiers en texte brut qui contiennent des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF signifie Data Interchange Format qui est utilisé pour importer/exporter des données de feuilles de calcul entre différentes applications. Ceux-ci incluent Microsoft Excel, OpenOffice Calc, StarCalc et bien d'autres. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Feuille de calcul XML plate OpenDocument |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Les fichiers avec l'extension .numbers sont classés comme type de fichier tableur, c'est pourquoi ils sont similaires aux fichiers .xlsx ; mais les fichiers Numbers sont créés à l'aide du logiciel de feuille de calcul Apple iWork Numbers. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Les fichiers avec l'extension ODS représentent le format de document de feuille de calcul OpenDocument modifiable par l'utilisateur. Les données sont stockées dans le fichier ODF en lignes et en colonnes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Modèle de feuille de calcul OpenDocument |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Un format basé sur XML utilisé par OpenOffice et StarOffice |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Un format de fichier de valeurs séparées par des tabulations (TSV) représente des données séparées par des tabulations au format texte brut. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | Format de document Xlam |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS représente le format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM est un type de fichier de feuille de calcul qui prend en charge les macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Les fichiers avec l'extension .XLT sont des fichiers modèles créés avec Microsoft Excel, un tableur faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | L'extension de fichier XLTM représente les fichiers générés par Microsoft Excel en tant que fichiers modèles prenant en charge les macros. Les fichiers XLTM sont similaires à XLTX dans leur structure, sauf que ce dernier ne prend pas en charge la création de fichiers modèles avec des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Le fichier XLTX représente le modèle Microsoft Excel basé sur les spécifications du format de fichier Office OpenXML. Il est utilisé pour créer un fichier de modèle standard qui peut être utilisé pour générer des fichiers XLSX qui présentent les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
