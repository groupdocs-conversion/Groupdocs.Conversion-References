---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Tabellenkalkulationsdokumenten."
type: docs
weight: 31
url: /de/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Optionen zum Laden von Tabellenkalkulationsdokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Initialisiert eine neue Instanz der Klasse [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSheets()](#getSheets--) | Blattname zum Konvertieren abrufen |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Blattname zum Konvertieren festlegen |
|
|  | [getCultureInfo()](#getCultureInfo--) | Systemkulturinformationen beim Laden der Datei abrufen |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Systemkulturinformationen beim Laden der Datei festlegen |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standard-Schriftart für Tabellenkalkulationsdokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standard-Schriftart für Tabellenkalkulationsdokument. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Bestimmte Schriftarten beim Konvertieren von Tabellenkalkulationsdokumenten ersetzen. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Bestimmte Schriftarten beim Konvertieren von Tabellenkalkulationsdokumenten ersetzen. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Gitternetzlinien beim Konvertieren von Excel-Dateien anzeigen. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Gitternetzlinien beim Konvertieren von Excel-Dateien anzeigen. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Versteckte Blätter beim Konvertieren von Excel-Dateien anzeigen. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Versteckte Blätter beim Konvertieren von Excel-Dateien anzeigen. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | Wenn OnePagePerSheet true ist, wird der Inhalt des Blatts zu einer Seite im PDF-Dokument konvertiert. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Wenn OnePagePerSheet true ist, wird der Inhalt des Blatts zu einer Seite im PDF-Dokument konvertiert. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Ermittelt die Eigenschaft AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Setzt die Eigenschaft AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | Wenn True und die Konvertierung zu PDF erfolgt, wird die Konvertierung für eine kleinere Dateigröße statt Druckqualität optimiert. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Wenn True und die Konvertierung zu PDF erfolgt, wird die Konvertierung für eine kleinere Dateigröße statt Druckqualität optimiert. |
|
|  | [getConvertRange()](#getConvertRange--) | Bestimmten Bereich konvertieren, wenn in ein anderes Format als Tabellenkalkulation konvertiert wird. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Bestimmten Bereich konvertieren, wenn in ein anderes Format als Tabellenkalkulation konvertiert wird. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Überspringt leere Zeilen und Spalten beim Konvertieren. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Überspringt leere Zeilen und Spalten beim Konvertieren. |
|
|  | [getPassword()](#getPassword--) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [getHideComments()](#getHideComments--) | Kommentare ausblenden. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Kommentare ausblenden. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Ob die Einschränkungen der Excel-Datei geprüft werden, wenn der Benutzer zellbezogene Objekte ändert. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Ruft die Liste der zu konvertierenden Blattindizes ab. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Legt die Liste der zu konvertierenden Blattindizes fest. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Passt alle Zeilen beim Konvertieren automatisch an |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Schriftordner vor dem Laden des Dokuments zurücksetzen. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Klont aktuelle Instanz. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Teilt ein Arbeitsblatt anhand von Zeilen in Seiten auf. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Teilt ein Arbeitsblatt anhand von Zeilen in Seiten auf. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Teilt ein Arbeitsblatt anhand von Spalten in Seiten auf. |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Teilt ein Arbeitsblatt anhand von Spalten in Seiten auf. |
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


Initialisiert eine neue Instanz der Klasse [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Blattname zum Konvertieren abrufen


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Blattname zum Konvertieren festlegen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Blätter | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Systemkulturinformationen beim Laden der Datei abrufen


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Systemkulturinformationen beim Laden der Datei festlegen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standard-Schriftart für das Tabellenkalkulationsdokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standard-Schriftart für das Tabellenkalkulationsdokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Bestimmte Schriftarten beim Konvertieren von Tabellenkalkulationsdokumenten ersetzen.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Bestimmte Schriftarten beim Konvertieren von Tabellenkalkulationsdokumenten ersetzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Gitternetzlinien beim Konvertieren von Excel-Dateien anzeigen.


**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Gitternetzlinien beim Konvertieren von Excel-Dateien anzeigen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Versteckte Blätter beim Konvertieren von Excel-Dateien anzeigen.


**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Versteckte Blätter beim Konvertieren von Excel-Dateien anzeigen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Wenn OnePagePerSheet wahr ist, wird der Inhalt des Blatts in eine Seite im PDF-Dokument konvertiert. Der Standardwert ist falsch.


**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Wenn OnePagePerSheet wahr ist, wird der Inhalt des Blatts in eine Seite im PDF-Dokument konvertiert. Der Standardwert ist falsch.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Ermittelt die Eigenschaft AllColumnsInOnePagePerSheet


**Returns:**
boolean - wahr, wenn alle Spalten auf eine Seite passen

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Setzt die Eigenschaft AllColumnsInOnePagePerSheet


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet-Eigenschaft |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Wenn True und die Konvertierung zu PDF erfolgt, wird die Konvertierung für eine kleinere Dateigröße statt Druckqualität optimiert.


**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Wenn True und die Konvertierung zu PDF erfolgt, wird die Konvertierung für eine kleinere Dateigröße statt Druckqualität optimiert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Konvertiere einen bestimmten Bereich, wenn in ein anderes Format als Tabellenkalkulation konvertiert wird. Beispiel: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Konvertiere einen bestimmten Bereich, wenn in ein anderes Format als Tabellenkalkulation konvertiert wird. Beispiel: "D1:F8".


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Überspringt leere Zeilen und Spalten beim Konvertieren. Standard ist wahr.


**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Überspringt leere Zeilen und Spalten beim Konvertieren. Standard ist wahr.


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

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Kommentare ausblenden.


**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Kommentare ausblenden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Ob die Einschränkungen der Excel-Datei geprüft werden, wenn der Benutzer zellbezogene Objekte ändert. Zum Beispiel erlaubt Excel nicht das Eingeben eines Zeichenkettenwertes, der länger als 32 KB ist. Wenn Sie einen Wert eingeben, der länger als 32 KB ist, erhalten Sie bei true dieser Eigenschaft eine Ausnahme. Ist diese Eigenschaft false, akzeptieren wir Ihren eingegebenen Zeichenkettenwert als Zellwert, sodass Sie später den vollständigen Zeichenkettenwert für andere Dateiformate wie CSV ausgeben können. Wenn Sie jedoch einen solchen Wert festlegen, der für das Excel-Dateiformat ungültig ist, sollten Sie die Arbeitsmappe später nicht im Excel-Format speichern. Andernfalls kann es zu unerwarteten Fehlern in der erzeugten Excel-Datei kommen.


**Returns:**
boolean - Flag zum Prüfen von Einschränkungen

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Ruft die Liste der zu konvertierenden Blattindizes ab.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Legt die Liste der zu konvertierenden Blattindizes fest. Die Indizes müssen bei Null beginnen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Passt alle Zeilen beim Konvertieren automatisch an


**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| autoFitRows | boolean |  |

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

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klont aktuelle Instanz.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Teilt ein Arbeitsblatt anhand von Zeilen in Seiten auf. Standard ist 0, keine Seitennummerierung.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Teilt ein Arbeitsblatt anhand von Zeilen in Seiten auf. Standard ist 0, keine Seitennummerierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Teilt ein Arbeitsblatt in Seiten nach Spalten. Standard ist 0, keine Paginierung.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Teilt ein Arbeitsblatt in Seiten nach Spalten. Standard ist 0, keine Paginierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ruft die Option ab, um zu steuern, ob der Dokumentcontainer selbst konvertiert werden muss


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option, um zu steuern, ob die im Dokumentcontainer enthaltenen Dokumente konvertiert werden müssen


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option, um zu steuern, wie viele Ebenen tief die Konvertierung durchgeführt werden soll


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tiefe | int |  |

