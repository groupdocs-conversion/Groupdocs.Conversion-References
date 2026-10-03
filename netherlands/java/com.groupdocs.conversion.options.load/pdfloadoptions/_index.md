---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van Pdf‑documenten."
type: docs
weight: 27
url: /nl/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opties voor het laden van Pdf‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Verwijder ingesloten bestanden. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Verwijder ingesloten bestanden. |
|
|  | [getPassword()](#getPassword--) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor Pdf-document. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor Pdf-document. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Vervang specifieke lettertypen bij het converteren van een Pdf-document. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Vervang specifieke lettertypen bij het converteren van een Pdf-document. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Verberg annotaties in Pdf-documenten. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Verberg annotaties in Pdf-documenten. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Vlak alle velden van het PDF-formulier. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Vlak alle velden van het PDF-formulier. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Reset lettertype-mappen vóór het laden van het document. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Schakel het genereren van paginanummering in het geconverteerde document in of uit. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Haalt de vlag Remove JavaScript op. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Stelt de vlag Remove JavaScript in. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Specificeert of het eigendocument moet worden geconverteerd. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Specificeert of het eigendocument moet worden geconverteerd. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Specificeert of eigendocumenten moeten worden geconverteerd. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Specificeert of eigendocumenten moeten worden geconverteerd. |
|
|  | [getDepth()](#getDepth--) | Maximumdiepte voor het verwerken van eigendocumenten. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Maximumdiepte voor het verwerken van eigendocumenten. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Invoerdocumentbestandstype


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
| waarde | boolean |  |

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
| waarde | java.lang.String |  |

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor Pdf-document.
Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor Pdf-document.
Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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
| waarde | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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
| waarde | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Vlak alle velden van het PDF-formulier.


**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Vlak alle velden van het PDF-formulier.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset lettertype-mappen vóór het laden van het document.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Schakel het genereren van paginanummering in het geconverteerde document in of uit. Standaard: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Haalt de vlag Remove JavaScript op.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Stelt de vlag Remove JavaScript in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Specificeert of het eigendocument moet worden geconverteerd.

Standaard is
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Specificeert of het eigendocument moet worden geconverteerd.

Standaard is
true
.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Specificeert of eigendocumenten moeten worden geconverteerd.

Standaard is
false
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Specificeert of eigendocumenten moeten worden geconverteerd.

Standaard is
false
.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Maximumdiepte voor het verwerken van eigendocumenten.

Standaard is
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Maximumdiepte voor het verwerken van eigendocumenten.

Standaard is
2
.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| depth | int |  |

