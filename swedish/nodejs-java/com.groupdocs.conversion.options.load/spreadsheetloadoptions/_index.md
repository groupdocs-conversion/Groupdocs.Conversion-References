---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för att ladda Spreadsheet-dokument."
type: docs
weight: 35
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Alternativ för att ladda Spreadsheet-dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Initierar en ny instans av klassen [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSheets()](#getSheets--) | Hämta bladnamn att konvertera |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Ange bladnamn att konvertera |
| [getCultureInfo()](#getCultureInfo--) | Hämta systemets kulturinformation när filen laddas |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Ange systemets kulturinformation när filen laddas |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för kalkylbladsdokument. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för kalkylbladsdokument. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Ersätt specifika teckensnitt vid konvertering av kalkylbladsdokument. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersätt specifika teckensnitt vid konvertering av kalkylbladsdokument. |
| [getShowGridLines()](#getShowGridLines--) | Visa rutnät när Excel-filer konverteras. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Visa rutnät när Excel-filer konverteras. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Visa dolda blad när Excel-filer konverteras. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Visa dolda blad när Excel-filer konverteras. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | Om OnePagePerSheet är sant kommer bladets innehåll att konverteras till en sida i PDF-dokumentet. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Om OnePagePerSheet är sant kommer bladets innehåll att konverteras till en sida i PDF-dokumentet. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Hämtar egenskapen AllColumnsInOnePagePerSheet. |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Ställer in egenskapen AllColumnsInOnePagePerSheet. |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | Om True och konvertering till PDF optimeras för bättre filstorlek än utskriftskvalitet. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Om True och konvertering till PDF optimeras för bättre filstorlek än utskriftskvalitet. |
| [getConvertRange()](#getConvertRange--) | Konvertera specifikt område när du konverterar till annat format än kalkylblad. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Konvertera specifikt område när du konverterar till annat format än kalkylblad. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Hoppar över tomma rader och kolumner vid konvertering. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Hoppar över tomma rader och kolumner vid konvertering. |
| [getPassword()](#getPassword--) | Ange lösenord för att avskydda skyddat dokument. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ange lösenord för att avskydda skyddat dokument. |
| [getHideComments()](#getHideComments--) | Dölj kommentarer. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Dölj kommentarer. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Om restriktioner för Excel-filen ska kontrolleras när användaren ändrar cellrelaterade objekt. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | Hämtar lista över bladindex att konvertera. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Ställer in lista över bladindex att konvertera. |
| [isAutoFitRows()](#isAutoFitRows--) | Anpassar automatiskt alla rader vid konvertering. |
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
| [getResetFontFolders()](#getResetFontFolders--) | Återställ teckensnittsmappar innan dokumentet laddas |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [deepClone()](#deepClone--) | Klonar aktuell instans. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Initierar en ny instans av klassen [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).

### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Hämta bladnamn att konvertera

**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Ange bladnamn att konvertera

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| blad | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Hämta systemets kulturinformation när filen laddas

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Ange systemets kulturinformation när filen laddas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Inmatningsdokumentets filtyp

**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för kalkylbladsdokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för kalkylbladsdokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ersätt specifika teckensnitt vid konvertering av kalkylbladsdokument.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ersätt specifika teckensnitt vid konvertering av kalkylbladsdokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Visa rutnät när Excel-filer konverteras.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Visa rutnät när Excel-filer konverteras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Visa dolda blad när Excel-filer konverteras.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Visa dolda blad när Excel-filer konverteras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Om OnePagePerSheet är true kommer innehållet i bladet att konverteras till en sida i PDF-dokumentet. Standardvärdet är false.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Om OnePagePerSheet är true kommer innehållet i bladet att konverteras till en sida i PDF-dokumentet. Standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Hämtar egenskapen AllColumnsInOnePagePerSheet.

**Returns:**
boolean - true om alla kolumner får plats på en sida
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Ställer in egenskapen AllColumnsInOnePagePerSheet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet egenskap |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Om True och konvertering till PDF optimeras för bättre filstorlek än utskriftskvalitet.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Om True och konvertering till PDF optimeras för bättre filstorlek än utskriftskvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Konvertera specifikt område när du konverterar till annat än kalkylbladsformat. Exempel: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Konvertera specifikt område när du konverterar till annat än kalkylbladsformat. Exempel: "D1:F8".

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Hoppar över tomma rader och kolumner vid konvertering. Standard är True.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Hoppar över tomma rader och kolumner vid konvertering. Standard är True.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ange lösenord för att avskydda skyddat dokument.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ange lösenord för att avskydda skyddat dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Dölj kommentarer.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Dölj kommentarer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Om restriktioner för Excel-filen ska kontrolleras när användaren ändrar cellrelaterade objekt. Till exempel tillåter inte Excel att ange ett strängvärde längre än 32K. När du anger ett värde längre än 32K, om denna egenskap är true, får du ett undantag. Om denna egenskap är false accepterar vi ditt inmatade strängvärde som cellens värde så att du senare kan skriva ut hela strängvärdet för andra filformat såsom CSV. Däremot, om du har angett ett värde som är ogiltigt för Excel-filformatet, bör du inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå oväntade fel i den genererade Excel-filen.

**Returns:**
boolean - flagga för att kontrollera restriktion
### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Hämtar lista över bladindex att konvertera.

**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Ställer in lista med bladindex att konvertera. Indexen måste vara nollbaserade

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Anpassar automatiskt alla rader vid konvertering.

**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Återställ teckensnittsmappar innan dokumentet laddas

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klonar aktuell instans.

**Returns:**
java.lang.Object -
