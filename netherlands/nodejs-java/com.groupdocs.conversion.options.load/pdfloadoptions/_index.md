---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van Pdf-documenten."
type: docs
weight: 31
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van Pdf-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Initialiseert een nieuw exemplaar van de [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Verwijder ingesloten bestanden. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Verwijder ingesloten bestanden. |
| [getPassword()](#getPassword--) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor Pdf-document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor Pdf-document. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Vervang specifieke lettertypen bij het converteren van een Pdf-document. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Vervang specifieke lettertypen bij het converteren van een Pdf-document. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Verberg annotaties in Pdf-documenten. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Verberg annotaties in Pdf-documenten. |
| [getFlattenAllFields()](#getFlattenAllFields--) | Vlak alle velden van het PDF-formulier af. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Vlak alle velden van het PDF-formulier af. |
| [getResetFontFolders()](#getResetFontFolders--) | Reset lettertype-mappen vóór het laden van het document |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initialiseert een nieuw exemplaar van de [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) klasse.

### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Verwijder ingesloten bestanden.

**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Verwijder ingesloten bestanden.

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor Pdf-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor Pdf-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Vervang specifieke lettertypen bij het converteren van een Pdf-document.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Vervang specifieke lettertypen bij het converteren van een Pdf-document.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Verberg annotaties in Pdf-documenten.

**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Verberg annotaties in Pdf-documenten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Vlak alle velden van het PDF-formulier af.

**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Vlak alle velden van het PDF-formulier af.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

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

