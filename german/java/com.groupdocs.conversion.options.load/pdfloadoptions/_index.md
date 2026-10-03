---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von PDF-Dokumenten."
type: docs
weight: 27
url: /de/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Optionen zum Laden von PDF-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Initialisiert eine neue Instanz der Klasse [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Eingebettete Dateien entfernen. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Eingebettete Dateien entfernen. |
|
|  | [getPassword()](#getPassword--) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Standard-Schriftart für PDF-Dokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standard-Schriftart für PDF-Dokument. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Bestimmte Schriftarten beim Konvertieren von PDF-Dokument ersetzen. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Bestimmte Schriftarten beim Konvertieren von PDF-Dokument ersetzen. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Anmerkungen in PDF-Dokumenten ausblenden. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Anmerkungen in PDF-Dokumenten ausblenden. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Alle Felder des PDF-Formulars flachlegen. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Alle Felder des PDF-Formulars flachlegen. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Schriftordner vor dem Laden des Dokuments zurücksetzen. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Ermöglicht oder deaktiviert die Erzeugung von Seitenzahlen im konvertierten Dokument. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Liest das Remove JavaScript-Flag. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Setzt das Remove JavaScript-Flag. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Gibt an, ob das übergeordnete Dokument konvertiert werden soll. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Gibt an, ob das übergeordnete Dokument konvertiert werden soll. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Gibt an, ob zugehörige Dokumente konvertiert werden sollen. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Gibt an, ob zugehörige Dokumente konvertiert werden sollen. |
|
|  | [getDepth()](#getDepth--) | Maximale Tiefe für die Verarbeitung zugehöriger Dokumente. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Maximale Tiefe für die Verarbeitung zugehöriger Dokumente. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Eingebettete Dateien entfernen.


**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Eingebettete Dateien entfernen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Passwort festlegen, um ein geschütztes Dokument zu entsperren.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Passwort festlegen, um ein geschütztes Dokument zu entsperren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standard-Schriftart für PDF-Dokument.
Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standard-Schriftart für PDF-Dokument.
Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Bestimmte Schriftarten beim Konvertieren von PDF-Dokument ersetzen.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Bestimmte Schriftarten beim Konvertieren von PDF-Dokument ersetzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Anmerkungen in PDF-Dokumenten ausblenden.


**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Anmerkungen in PDF-Dokumenten ausblenden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Alle Felder des PDF-Formulars flachlegen.


**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Alle Felder des PDF-Formulars flachlegen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Schriftordner vor dem Laden des Dokuments zurücksetzen.


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktiviert oder deaktiviert die Erzeugung von Seitenzahlen im konvertierten Dokument. Standard: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Liest das Remove JavaScript-Flag.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Setzt das Remove JavaScript-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Gibt an, ob das übergeordnete Dokument konvertiert werden soll.

Standard ist
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Gibt an, ob das übergeordnete Dokument konvertiert werden soll.

Standard ist
true
.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Gibt an, ob zugehörige Dokumente konvertiert werden sollen.

Standard ist
false
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Gibt an, ob zugehörige Dokumente konvertiert werden sollen.

Standard ist
false
.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Maximale Tiefe für die Verarbeitung zugehöriger Dokumente.

Standard ist
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Maximale Tiefe für die Verarbeitung zugehöriger Dokumente.

Standard ist
2
.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tiefe | int |  |

