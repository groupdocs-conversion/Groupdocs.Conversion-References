---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van Spreadsheet-documenten."
type: docs
weight: 35
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Opties voor het laden van Spreadsheet-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSheets()](#getSheets--) | Haal bladnaam op om te converteren |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Stel de bladnaam in om te converteren |
| [getCultureInfo()](#getCultureInfo--) | Haal de systeemcultuurinfo op op het moment dat het bestand wordt geladen |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Stel de systeemcultuurinfo in op het moment dat het bestand wordt geladen |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor spreadsheetdocument. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor spreadsheetdocument. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Vervang specifieke lettertypen bij het converteren van een spreadsheetdocument. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Vervang specifieke lettertypen bij het converteren van een spreadsheetdocument. |
| [getShowGridLines()](#getShowGridLines--) | Toon rasterlijnen bij het converteren van Excel-bestanden. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Toon rasterlijnen bij het converteren van Excel-bestanden. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Toon verborgen bladen bij het converteren van Excel-bestanden. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Toon verborgen bladen bij het converteren van Excel-bestanden. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | Als OnePagePerSheet true is, wordt de inhoud van het blad geconverteerd naar één pagina in het PDF-document. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Als OnePagePerSheet true is, wordt de inhoud van het blad geconverteerd naar één pagina in het PDF-document. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Haalt de eigenschap AllColumnsInOnePagePerSheet op |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Stelt de eigenschap AllColumnsInOnePagePerSheet in |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | Als True en er wordt geconverteerd naar PDF, is de conversie geoptimaliseerd voor een kleinere bestandsgrootte dan afdrukkwaliteit. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Als True en er wordt geconverteerd naar PDF, is de conversie geoptimaliseerd voor een kleinere bestandsgrootte dan afdrukkwaliteit. |
| [getConvertRange()](#getConvertRange--) | Converteer een specifiek bereik bij het converteren naar een ander formaat dan spreadsheet. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Converteer een specifiek bereik bij het converteren naar een ander formaat dan spreadsheet. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Slaat lege rijen en kolommen over bij het converteren. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Slaat lege rijen en kolommen over bij het converteren. |
| [getPassword()](#getPassword--) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [getHideComments()](#getHideComments--) | Verberg opmerkingen. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Verberg opmerkingen. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Of de beperking van het Excel-bestand wordt gecontroleerd wanneer de gebruiker cell-gerelateerde objecten wijzigt. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | Haalt de lijst met bladindexen op om te converteren. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Stelt de lijst met bladindexen in om te converteren. |
| [isAutoFitRows()](#isAutoFitRows--) | Past alle rijen automatisch aan bij het converteren |
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
| [getResetFontFolders()](#getResetFontFolders--) | Reset lettertype-mappen vóór het laden van het document |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [deepClone()](#deepClone--) | Kloont huidige instantie. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).

### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Haal bladnaam op om te converteren

**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Stel de bladnaam in om te converteren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bladen | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Haal de systeemcultuurinfo op op het moment dat het bestand wordt geladen

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Stel de systeemcultuurinfo in op het moment dat het bestand wordt geladen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor spreadsheetdocument. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor spreadsheetdocument. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Vervang specifieke lettertypen bij het converteren van een spreadsheetdocument.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Vervang specifieke lettertypen bij het converteren van een spreadsheetdocument.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Toon rasterlijnen bij het converteren van Excel-bestanden.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Toon rasterlijnen bij het converteren van Excel-bestanden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Toon verborgen bladen bij het converteren van Excel-bestanden.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Toon verborgen bladen bij het converteren van Excel-bestanden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Als OnePagePerSheet true is, wordt de inhoud van het blad geconverteerd naar één pagina in het PDF-document. Standaardwaarde is false.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Als OnePagePerSheet true is, wordt de inhoud van het blad geconverteerd naar één pagina in het PDF-document. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Haalt de eigenschap AllColumnsInOnePagePerSheet op

**Returns:**
boolean - true als alle kolommen op één pagina passen
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Stelt de eigenschap AllColumnsInOnePagePerSheet in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet eigenschap |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Als True en er wordt geconverteerd naar PDF, is de conversie geoptimaliseerd voor een kleinere bestandsgrootte dan afdrukkwaliteit.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Als True en er wordt geconverteerd naar PDF, is de conversie geoptimaliseerd voor een kleinere bestandsgrootte dan afdrukkwaliteit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Converteer een specifiek bereik bij het converteren naar een ander formaat dan spreadsheet. Voorbeeld: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Converteer een specifiek bereik bij het converteren naar een ander formaat dan spreadsheet. Voorbeeld: "D1:F8".

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Slaat lege rijen en kolommen over bij het converteren. Standaard is True.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Slaat lege rijen en kolommen over bij het converteren. Standaard is True.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Stel wachtwoord in om een beschermd document te ontgrendelen.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stel wachtwoord in om een beschermd document te ontgrendelen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Verberg opmerkingen.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Verberg opmerkingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Of de beperking van een Excel‑bestand moet worden gecontroleerd wanneer de gebruiker gerelateerde celobjecten wijzigt. Bijvoorbeeld, Excel staat niet toe dat een tekenreeks langer dan 32 K wordt ingevoerd. Wanneer je een waarde langer dan 32 K invoert, krijg je een Exception als deze eigenschap true is. Als deze eigenschap false is, accepteren we je ingevoerde tekenreeks als de celwaarde, zodat je later de volledige tekenreeks kunt exporteren naar andere bestandsformaten zoals CSV. Als je echter een waarde hebt ingesteld die ongeldig is voor het Excel‑bestandformaat, moet je het werkboek later niet opslaan als Excel‑bestandformaat. Anders kan er een onverwachte fout optreden in het gegenereerde Excel‑bestand.

**Returns:**
boolean - controleer restrictievlag
### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Haalt de lijst met bladindexen op om te converteren.

**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Stelt de lijst met blad‑indexen in die moeten worden geconverteerd. De indexen moeten nulgebaseerd zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Past alle rijen automatisch aan bij het converteren

**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset lettertype-mappen vóór het laden van het document

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloont huidige instantie.

**Returns:**
java.lang.Object -
