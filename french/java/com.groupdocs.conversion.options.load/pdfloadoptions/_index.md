---
title: "PdfLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents PDF."
type: docs
weight: 27
url: /fr/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Options de chargement des documents PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Initialise une nouvelle instance de la classe [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Supprimer les fichiers incorporés. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Supprimer les fichiers incorporés. |
|
|  | [getPassword()](#getPassword--) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Police par défaut pour le document Pdf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Police par défaut pour le document Pdf. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Remplacer les polices spécifiques lors de la conversion du document Pdf. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Remplacer les polices spécifiques lors de la conversion du document Pdf. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Masquer les annotations dans les documents Pdf. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Masquer les annotations dans les documents Pdf. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Aplatir tous les champs du formulaire PDF. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Aplatir tous les champs du formulaire PDF. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Réinitialiser les dossiers de polices avant de charger le document. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Activer ou désactiver la génération de la numérotation des pages dans le document converti. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Obtient le drapeau Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Définit le drapeau Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Spécifie si le document propriétaire doit être converti. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Spécifie si le document propriétaire doit être converti. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Spécifie si les documents détenus doivent être convertis. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Spécifie si les documents détenus doivent être convertis. |
|
|  | [getDepth()](#getDepth--) | Profondeur maximale pour le traitement des documents détenus. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Profondeur maximale pour le traitement des documents détenus. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initialise une nouvelle instance de la classe [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Supprimer les fichiers incorporés.


**Returns:**
booléen
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Supprimer les fichiers incorporés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Police par défaut pour le document Pdf.
La police suivante sera utilisée si une police est manquante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Police par défaut pour le document Pdf.
La police suivante sera utilisée si une police est manquante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Remplacer les polices spécifiques lors de la conversion du document Pdf.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Remplacer les polices spécifiques lors de la conversion du document Pdf.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Masquer les annotations dans les documents Pdf.


**Returns:**
booléen
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Masquer les annotations dans les documents Pdf.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Aplatir tous les champs du formulaire PDF.


**Returns:**
booléen
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Aplatir tous les champs du formulaire PDF.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Réinitialiser les dossiers de polices avant de charger le document.


**Returns:**
booléen
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resetFontFolders | booléen |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Activer ou désactiver la génération de la numérotation des pages dans le document converti. Valeur par défaut: false.


**Returns:**
booléen
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isPageNumbering | booléen |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Obtient le drapeau Remove JavaScript.


**Returns:**
booléen
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Définit le drapeau Remove JavaScript.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| removeJavascript | booléen |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Spécifie si le document propriétaire doit être converti.

Par défaut est
true
.


**Returns:**
booléen
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Spécifie si le document propriétaire doit être converti.

Par défaut est
true
.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwner | booléen |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Spécifie si les documents détenus doivent être convertis.

Par défaut est
false
.


**Returns:**
booléen
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Spécifie si les documents détenus doivent être convertis.

Par défaut est
false
.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwned | booléen |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Profondeur maximale pour le traitement des documents détenus.

Par défaut est
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Profondeur maximale pour le traitement des documents détenus.

Par défaut est
2
.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| depth | int |  |

