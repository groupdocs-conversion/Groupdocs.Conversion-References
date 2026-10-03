---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för att läsa in PDF-dokument."
type: docs
weight: 27
url: /sv/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Alternativ för att läsa in PDF-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Initierar en ny instans av klassen [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Ta bort inbäddade filer. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Ta bort inbäddade filer. |
|
|  | [getPassword()](#getPassword--) | Ange lösenord för att avskydda skyddat dokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ange lösenord för att avskydda skyddat dokument. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för Pdf-dokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för Pdf-dokument. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ersätt specifika teckensnitt vid konvertering av Pdf-dokument. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersätt specifika teckensnitt vid konvertering av Pdf-dokument. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Dölj annotationer i Pdf-dokument. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Dölj annotationer i Pdf-dokument. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Platta till alla fält i PDF-formuläret. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Platta till alla fält i PDF-formuläret. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Återställ teckensnittsmappar innan dokumentet laddas. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Aktivera eller inaktivera generering av sidnumrering i konverterat dokument. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Hämtar flaggan Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Ställer in flaggan Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Anger om ägardokumentet ska konverteras. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Anger om ägardokumentet ska konverteras. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Anger om ägda dokument ska konverteras. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Anger om ägda dokument ska konverteras. |
|
|  | [getDepth()](#getDepth--) | Maximalt djup för bearbetning av ägda dokument. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Maximalt djup för bearbetning av ägda dokument. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initierar en ny instans av klassen [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Dokumentfiltyp för inmatning


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Ta bort inbäddade filer.


**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Ta bort inbäddade filer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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
| värde | java.lang.String |  |

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för Pdf-dokument.
Följande teckensnitt kommer att användas om ett teckensnitt saknas.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för Pdf-dokument.
Följande teckensnitt kommer att användas om ett teckensnitt saknas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ersätt specifika teckensnitt vid konvertering av Pdf-dokument.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ersätt specifika teckensnitt vid konvertering av Pdf-dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Dölj annotationer i Pdf-dokument.


**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Dölj annotationer i Pdf-dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Platta till alla fält i PDF-formuläret.


**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Platta till alla fält i PDF-formuläret.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Återställ teckensnittsmappar innan dokumentet laddas.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktivera eller inaktivera generering av sidnumrering i konverterat dokument. Standard: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Hämtar flaggan Remove JavaScript.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Ställer in flaggan Remove JavaScript.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Anger om ägardokumentet ska konverteras.

Standard är
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Anger om ägardokumentet ska konverteras.

Standard är
true
.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Anger om ägda dokument ska konverteras.

Standard är
false
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Anger om ägda dokument ska konverteras.

Standard är
false
.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Maximalt djup för bearbetning av ägda dokument.

Standard är
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Maximalt djup för bearbetning av ägda dokument.

Standard är
2
.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| depth | int |  |

