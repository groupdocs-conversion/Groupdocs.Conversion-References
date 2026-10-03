---
title: "SpreadsheetFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents de feuille de calcul."
type: docs
weight: 25
url: /fr/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Définit les documents de feuille de calcul. Inclut les types de fichiers suivants :
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
En savoir plus sur les formats de feuilles de calcul [ici](../https://wiki.fileformat.com/spreadsheet).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Xls](#Xls) | XLS représente le format de fichier binaire Excel. |
|
|  | [Xlsx](#Xlsx) | XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. |
|
|  | [Xlsm](#Xlsm) | XLSM est un type de fichiers de feuille de calcul qui prend en charge les macros. |
|
|  | [Xlsb](#Xlsb) | Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures définissant le contenu d'un classeur Excel. |
|
|  | [Ods](#Ods) | Les fichiers avec l'extension ODS correspondent au format de document de feuille de calcul OpenDocument qui est modifiable par l'utilisateur. |
|
|  | [Ots](#Ots) | Un fichier avec l'extension .ots est un modèle de feuille de calcul OpenDocument créé avec le logiciel Calc inclus dans Apache OpenOffice. |
|
|  | [Xltx](#Xltx) | Le fichier XLTX représente un modèle Microsoft Excel basé sur les spécifications du format de fichier Office OpenXML. |
|
|  | [Xlt](#Xlt) | Les fichiers avec l'extension .XLT sont des modèles créés avec Microsoft Excel, qui est une application de feuille de calcul faisant partie de la suite Microsoft Office. |
|
|  | [Xltm](#Xltm) | L'extension de fichier XLTM représente des fichiers générés par Microsoft Excel en tant que modèles activés par macro. |
|
|  | [Tsv](#Tsv) | Un format de fichier Valeurs séparées par des tabulations (TSV) représente des données séparées par des tabulations au format texte brut. |
|
|  | [Xlam](#Xlam) | XLAM est un fichier d'extension activée par macro utilisé pour ajouter de nouvelles fonctions aux feuilles de calcul. |
|
|  | [Csv](#Csv) | Les fichiers avec l'extension CSV (Valeurs séparées par des virgules) représentent des fichiers texte brut contenant des enregistrements de données avec des valeurs séparées par des virgules. |
|
|  | [Fods](#Fods) | Un fichier avec l'extension .fods est un type de format de document de feuille de calcul OpenDocument qui stocke les données en lignes et colonnes. |
|
|  | [Dif](#Dif) | DIF signifie Data Interchange Format, qui est utilisé pour importer/exporter des données de feuilles de calcul entre différentes applications. |
|
|  | [Sxc](#Sxc) | Le format de fichier SXC (Sun XML Calc) appartient à une suite bureautique appelée OpenOffice.org. |
|
|  | [Numbers](#Numbers) | Les fichiers avec l’extension .numbers sont classés comme type de fichier de feuille de calcul, c’est pourquoi ils sont similaires aux fichiers .xlsx ; mais les fichiers Numbers sont créés en utilisant le logiciel de tableur Apple iWork Numbers. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Constructeur de sérialisation


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS représente le format de fichier binaire Excel. De tels fichiers peuvent être créés par Microsoft Excel ainsi que par d’autres programmes de tableur similaires tels qu’OpenOffice Calc ou Apple Numbers.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM est un type de fichiers de feuille de calcul qui prend en charge les macros.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures définissant le contenu d'un classeur Excel.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


Les fichiers avec l’extension ODS désignent le format de document de feuille de calcul OpenDocument, qui est modifiable par l’utilisateur. Les données sont stockées dans le fichier ODF sous forme de lignes et de colonnes.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


Un fichier avec l’extension .ots est un modèle de feuille de calcul OpenDocument créé avec le logiciel Calc inclus dans Apache OpenOffice. Le logiciel Calc est similaire à Excel disponible dans Microsoft Office.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


Le fichier XLTX représente un modèle Microsoft Excel basé sur les spécifications du format de fichier Office OpenXML. Il est utilisé pour créer un fichier modèle standard qui peut être utilisé pour générer des fichiers XLSX présentant les mêmes paramètres que ceux spécifiés dans le fichier XLTX.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


Les fichiers avec l’extension .XLT sont des fichiers modèle créés avec Microsoft Excel, qui est une application de feuille de calcul faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


L’extension de fichier XLTM représente des fichiers générés par Microsoft Excel en tant que modèles activés par des macros. Les fichiers XLTM sont similaires aux XLTX sur le plan de la structure, à la différence que ces derniers ne prennent pas en charge la création de modèles contenant des macros.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Un format de fichier Valeurs séparées par des tabulations (TSV) représente des données séparées par des tabulations au format texte brut.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM est un fichier d’extension Macro-Enabled Add-In qui sert à ajouter de nouvelles fonctions aux feuilles de calcul. Un Add-In est un programme supplémentaire qui exécute du code additionnel et fournit des fonctionnalités supplémentaires aux feuilles de calcul.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


Les fichiers avec l'extension CSV (Valeurs séparées par des virgules) représentent des fichiers texte brut contenant des enregistrements de données avec des valeurs séparées par des virgules.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


Un fichier avec l’extension .fods est un type de format de document de feuille de calcul OpenDocument qui stocke les données en lignes et colonnes. Ce format est spécifié dans le cadre des spécifications ODF 1.2 publiées et maintenues par OASIS. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF signifie Data Interchange Format qui est utilisé pour importer/exporter des données de feuilles de calcul entre différentes applications. Celles‑ci incluent Microsoft Excel, OpenOffice Calc, StarCalc et bien d’autres. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Le format de fichier SXC (Sun XML Calc) appartient à une suite bureautique appelée OpenOffice.org. Ce format répond généralement aux besoins de feuilles de calcul des utilisateurs car il s'agit d'un format de fichier de feuille de calcul basé sur XML. Le format SXC prend en charge les formules, les fonctions, les macros et les graphiques ainsi que DataPilot. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


Les fichiers avec l’extension .numbers sont classés comme type de fichier de feuille de calcul, c’est pourquoi ils sont similaires aux fichiers .xlsx ; mais les fichiers Numbers sont créés à l’aide du logiciel de feuille de calcul Apple iWork Numbers. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/spreadsheet/numbers).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion par défaut préparées pour le type de fichier


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
