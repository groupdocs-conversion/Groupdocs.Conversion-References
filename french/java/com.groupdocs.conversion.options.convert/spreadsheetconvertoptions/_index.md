---
title: "SpreadsheetConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de conversion vers le type de fichier Spreadsheet."
type: docs
weight: 40
url: /fr/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Options de conversion vers le type de fichier Spreadsheet.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Initialise une nouvelle instance de la classe [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
|
|  | [getZoom()](#getZoom--) | Spécifie le niveau de zoom en pourcentage. |
|
|  | [setZoom(int value)](#setZoom-int-) | Spécifie le niveau de zoom en pourcentage. |
|
|  | [getSeparator()](#getSeparator--) | Spécifie le séparateur à utiliser lors de la conversion vers des formats délimités |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Initialise une nouvelle instance de la classe [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Spécifie le séparateur à utiliser lors de la conversion vers des formats délimités


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| séparateur | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Le type de fichier souhaité vers lequel le document d'entrée doit être converti.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

