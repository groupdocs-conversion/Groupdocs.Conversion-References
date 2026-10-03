---
title: "NoteLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents One."
type: docs
weight: 24
url: /fr/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Options de chargement des documents One.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | Initialise une nouvelle instance de la classe [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Police par défaut pour le document Note. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Police par défaut pour le document Note. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Remplace les polices spécifiques lors de la conversion du document Note. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Remplace les polices spécifiques lors de la conversion du document Note. |
|
|  | [getPassword()](#getPassword--) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définir le mot de passe pour déprotéger le document protégé. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Initialise une nouvelle instance de la classe [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Police par défaut pour le document Note. La police suivante sera utilisée si une police est manquante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Police par défaut pour le document Note. La police suivante sera utilisée si une police est manquante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Remplace les polices spécifiques lors de la conversion du document Note.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Remplace les polices spécifiques lors de la conversion du document Note.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Définir le mot de passe pour déprotéger le document protégé.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définir le mot de passe pour déprotéger le document protégé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

