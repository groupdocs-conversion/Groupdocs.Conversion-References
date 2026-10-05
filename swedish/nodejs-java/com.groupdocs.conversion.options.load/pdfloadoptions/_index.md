---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för att ladda Pdf-dokument."
type: docs
weight: 31
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Alternativ för att ladda Pdf-dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Initierar en ny instans av klassen [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Ta bort inbäddade filer. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Ta bort inbäddade filer. |
| [getPassword()](#getPassword--) | Ange lösenord för att avskydda skyddat dokument. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ange lösenord för att avskydda skyddat dokument. |
| [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för Pdf-dokument. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för Pdf-dokument. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Ersätt specifika teckensnitt vid konvertering av Pdf-dokument. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersätt specifika teckensnitt vid konvertering av Pdf-dokument. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Dölj annotationer i Pdf-dokument. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Dölj annotationer i Pdf-dokument. |
| [getFlattenAllFields()](#getFlattenAllFields--) | Platta till alla fält i PDF-formuläret. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Platta till alla fält i PDF-formuläret. |
| [getResetFontFolders()](#getResetFontFolders--) | Återställ teckensnittsmappar innan dokumentet laddas |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initierar en ny instans av klassen [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).

### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Inmatningsdokumentets filtyp

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för Pdf-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för Pdf-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

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
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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
| value | boolean |  |

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
| value | boolean |  |

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

