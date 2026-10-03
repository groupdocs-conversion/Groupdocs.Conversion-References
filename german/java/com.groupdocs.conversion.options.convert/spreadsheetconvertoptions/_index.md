---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Tabellenkalkulationsdateityp."
type: docs
weight: 40
url: /de/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Optionen für die Konvertierung zum Tabellenkalkulationsdateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Initialisiert eine neue Instanz der Klasse [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
|
|  | [getZoom()](#getZoom--) | Gibt den Zoom‑Wert in Prozent an. |
|
|  | [setZoom(int value)](#setZoom-int-) | Gibt den Zoom‑Wert in Prozent an. |
|
|  | [getSeparator()](#getSeparator--) | Gibt das Trennzeichen an, das bei der Konvertierung in ein durch Trennzeichen getrenntes Format verwendet wird. |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Initialisiert eine neue Instanz der Klasse [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Gibt das Trennzeichen an, das bei der Konvertierung in ein durch Trennzeichen getrenntes Format verwendet wird.


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Trennzeichen | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

