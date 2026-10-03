---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von One-Dokumenten."
type: docs
weight: 24
url: /de/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Optionen zum Laden von One-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | Initialisiert eine neue Instanz der Klasse [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standard-Schriftart für Note-Dokument. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standard-Schriftart für Note-Dokument. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Spezifische Schriftarten beim Konvertieren des Note-Dokuments ersetzen. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Spezifische Schriftarten beim Konvertieren des Note-Dokuments ersetzen. |
|
|  | [getPassword()](#getPassword--) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Passwort festlegen, um ein geschütztes Dokument zu entsperren. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standard-Schriftart für Note-Dokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standard-Schriftart für Note-Dokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Spezifische Schriftarten beim Konvertieren des Note-Dokuments ersetzen.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Spezifische Schriftarten beim Konvertieren des Note-Dokuments ersetzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

