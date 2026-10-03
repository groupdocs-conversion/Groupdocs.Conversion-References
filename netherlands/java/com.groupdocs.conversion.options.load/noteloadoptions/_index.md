---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van One‑documenten."
type: docs
weight: 24
url: /nl/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van One‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor Note-document. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor Note-document. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Vervang specifieke lettertypen bij het converteren van een Note-document. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Vervang specifieke lettertypen bij het converteren van een Note-document. |
|
|  | [getPassword()](#getPassword--) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Invoerdocumentbestandstype


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor Note-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor Note-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Vervang specifieke lettertypen bij het converteren van een Note-document.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Vervang specifieke lettertypen bij het converteren van een Note-document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

