---
title: "SpreadsheetLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents de feuille de calcul."
type: docs
weight: 31
url: /fr/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Options de chargement des documents de feuille de calcul.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Initialise une nouvelle instance de la classe [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSheets()](#getSheets--) | Obtenir le nom de la feuille à convertir |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Définir le nom de la feuille à convertir |
|
|  | [getCultureInfo()](#getCultureInfo--) | Obtenir les informations de culture du système au moment où le fichier est chargé |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Définir les informations de culture du système au moment où le fichier est chargé |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Police par défaut pour le document de tableur. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Police par défaut pour le document de tableur. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Remplacer des polices spécifiques lors de la conversion du document de tableur. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Remplacer des polices spécifiques lors de la conversion du document de tableur. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Afficher les lignes de grille lors de la conversion des fichiers Excel. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Afficher les lignes de grille lors de la conversion des fichiers Excel. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Afficher les feuilles cachées lors de la conversion des fichiers Excel. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Afficher les feuilles cachées lors de la conversion des fichiers Excel. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | Si OnePagePerSheet est vrai, le contenu de la feuille sera converti en une page dans le document PDF. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Si OnePagePerSheet est vrai, le contenu de la feuille sera converti en une page dans le document PDF. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Obtient la propriété AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Définit la propriété AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | Si True et que la conversion vers PDF, la conversion est optimisée pour une meilleure taille de fichier au détriment de la qualité d'impression. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Si True et que la conversion vers PDF, la conversion est optimisée pour une meilleure taille de fichier au détriment de la qualité d'impression. |
|
|  | [getConvertRange()](#getConvertRange--) | Convertir une plage spécifique lors de la conversion vers un format autre que le format tableur. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Convertir une plage spécifique lors de la conversion vers un format autre que le format tableur. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Ignore les lignes et colonnes vides lors de la conversion. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Ignore les lignes et colonnes vides lors de la conversion. |
|
|  | [getPassword()](#getPassword--) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [getHideComments()](#getHideComments--) | Masquer les commentaires. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Masquer les commentaires. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Indique s'il faut vérifier les restrictions du fichier Excel lorsque l'utilisateur modifie les objets liés aux cellules. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Obtient la liste des index de feuilles à convertir. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Définit la liste des index de feuilles à convertir. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Ajuste automatiquement toutes les lignes lors de la conversion |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Réinitialiser les dossiers de polices avant le chargement du document |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Clone l'instance actuelle. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Diviser une feuille de calcul en pages par lignes. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Diviser une feuille de calcul en pages par lignes. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Diviser une feuille de calcul en pages par colonnes. |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Diviser une feuille de calcul en pages par colonnes. |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Initialise une nouvelle instance de la classe [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Obtenir le nom de la feuille à convertir


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Définir le nom de la feuille à convertir


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| feuilles | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Obtenir les informations de culture du système au moment où le fichier est chargé


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Définir les informations de culture du système au moment où le fichier est chargé


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Police par défaut pour le document de feuille de calcul. La police suivante sera utilisée si une police est manquante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Police par défaut pour le document de feuille de calcul. La police suivante sera utilisée si une police est manquante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Remplacer des polices spécifiques lors de la conversion du document de tableur.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Remplacer des polices spécifiques lors de la conversion du document de tableur.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Afficher les lignes de grille lors de la conversion des fichiers Excel.


**Returns:**
booléen
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Afficher les lignes de grille lors de la conversion des fichiers Excel.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Afficher les feuilles cachées lors de la conversion des fichiers Excel.


**Returns:**
booléen
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Afficher les feuilles cachées lors de la conversion des fichiers Excel.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Si OnePagePerSheet est vrai, le contenu de la feuille sera converti en une page dans le document PDF. La valeur par défaut est false.


**Returns:**
booléen
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Si OnePagePerSheet est vrai, le contenu de la feuille sera converti en une page dans le document PDF. La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Obtient la propriété AllColumnsInOnePagePerSheet


**Returns:**
booléen - true si toutes les colonnes sont ajustées à une page

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Définit la propriété AllColumnsInOnePagePerSheet


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | booléen | Propriété AllColumnsInOnePagePerSheet |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Si True et que la conversion vers PDF, la conversion est optimisée pour une meilleure taille de fichier au détriment de la qualité d'impression.


**Returns:**
booléen
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Si True et que la conversion vers PDF, la conversion est optimisée pour une meilleure taille de fichier au détriment de la qualité d'impression.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Convertir une plage spécifique lors de la conversion vers un format autre que la feuille de calcul. Exemple : "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Convertir une plage spécifique lors de la conversion vers un format autre que la feuille de calcul. Exemple : "D1:F8".


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Ignore les lignes et colonnes vides lors de la conversion. La valeur par défaut est True.


**Returns:**
booléen
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Ignore les lignes et colonnes vides lors de la conversion. La valeur par défaut est True.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Définir le mot de passe pour déprotéger le document protégé.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définir le mot de passe pour déprotéger le document protégé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Masquer les commentaires.


**Returns:**
booléen
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Masquer les commentaires.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Indique si la restriction du fichier Excel doit être vérifiée lorsque l'utilisateur modifie des objets liés aux cellules. Par exemple, Excel n'autorise pas la saisie d'une chaîne de caractères supérieure à 32 K. Lorsque vous saisissez une valeur supérieure à 32 K, si cette propriété est true, vous obtiendrez une Exception. Si cette propriété est false, nous accepterons votre chaîne saisie comme valeur de la cellule afin que vous puissiez ensuite exporter la chaîne complète vers d'autres formats de fichier tels que CSV. Cependant, si vous avez défini une valeur de ce type qui n'est pas valide pour le format de fichier Excel, vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, des erreurs inattendues peuvent survenir dans le fichier Excel généré.


**Returns:**
booléen - drapeau de vérification de restriction

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| checkExcelRestriction | booléen |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Obtient la liste des index de feuilles à convertir.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Définit la liste des index de feuilles à convertir. Les index doivent être basés sur zéro.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Ajuste automatiquement toutes les lignes lors de la conversion


**Returns:**
booléen
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autoFitRows | booléen |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Réinitialiser les dossiers de polices avant le chargement du document


**Returns:**
booléen
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resetFontFolders | booléen |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clone l'instance actuelle.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Divise une feuille de calcul en pages par lignes. La valeur par défaut est 0, aucune pagination.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Divise une feuille de calcul en pages par lignes. La valeur par défaut est 0, aucune pagination.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Divise une feuille de calcul en pages par colonnes. La valeur par défaut est 0, aucune pagination.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Divise une feuille de calcul en pages par colonnes. La valeur par défaut est 0, aucune pagination.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtient l'option permettant de contrôler si le conteneur du document doit être converti


**Returns:**
booléen
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwner | booléen |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option pour contrôler si les documents possédés dans le conteneur de documents doivent être convertis


**Returns:**
booléen
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwned | booléen |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option pour contrôler le nombre de niveaux de profondeur à convertir


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| depth | int |  |

