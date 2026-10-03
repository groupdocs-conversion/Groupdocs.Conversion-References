---
title: "WordProcessingLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour le chargement des documents WordProcessing."
type: docs
weight: 40
url: /fr/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Options pour le chargement des documents WordProcessing.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Initialise une nouvelle instance de la classe [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Police par défaut pour le document Words. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Police par défaut pour le document Words. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Si AutoFontSubstitution est désactivé, GroupDocs.Conversion utilise DefaultFont pour la substitution des polices manquantes. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Si AutoFontSubstitution est désactivé, GroupDocs.Conversion utilise DefaultFont pour la substitution des polices manquantes. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Remplace les polices spécifiques lors de la conversion d'un document Words. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Si EmbedTrueTypeFonts est vrai, GroupDocs.Conversion intègre les polices TrueType dans le document de sortie. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Met à jour la mise en page après le chargement. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Met à jour les champs après le chargement. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Conserve la valeur originale du champ date. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Définit la conservation de la valeur originale du champ date. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Remplace les polices spécifiques lors de la conversion d'un document Words. |
|
|  | [getPassword()](#getPassword--) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définir le mot de passe pour déprotéger le document protégé. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Masquer le balisage et le suivi des modifications pour les documents Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Masquer le balisage et le suivi des modifications pour les documents Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Masquer les commentaires. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Options des signets |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Options des signets |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Spécifie s'il faut conserver les champs de formulaire Microsoft Word en tant que champs de formulaire dans le PDF ou les convertir en texte. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Définit le drapeau preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Spécifie s'il faut utiliser un formateur de texte pour un meilleur affichage du crénage. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Spécifie s'il faut utiliser un formateur de texte pour un meilleur affichage du crénage. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Détermine si la structure du document doit être conservée lors de la conversion en PDF (false par défaut). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Spécifie comment les commentaires doivent être affichés dans le document de sortie. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Afficher le nom complet du commentateur dans les commentaires. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Activer ou désactiver la génération de la numérotation des pages dans le document converti. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Obtient les options de césure pour les documents WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Définit les options de césure pour les documents WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Obtient le drapeau InterruptThreadIfImageExceptionThrown. Valeur par défaut : false. Si vrai, interrompt le thread principal de conversion lorsqu’une exception dans un thread de traitement d’image s’est produite. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Définit le drapeau InterruptThreadIfImageExceptionThrown. |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Lorsqu’il est activé (par défaut), les paragraphes et les runs dont le texte est majoritairement de droite à gauche (RTL) verront leurs drapeaux bidi réparés avant la conversion. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Définit autoDetectRtlDirection. |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Initialise une nouvelle instance de la classe [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Police par défaut pour les documents Words. La police suivante sera utilisée si une police est manquante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Police par défaut pour les documents Words. La police suivante sera utilisée si une police est manquante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Si AutoFontSubstitution est désactivé, GroupDocs.Conversion utilise DefaultFont pour la substitution des polices manquantes. Si AutoFontSubstitution est activé,
GroupDocs.Conversion évalue tous les champs associés dans FontInfo (Panose, Sig, etc.) pour la police manquante et trouve la correspondance la plus proche parmi les sources de polices disponibles.
Notez que le mécanisme de substitution de police remplacera DefaultFont dans les cas où FontInfo pour la police manquante est disponible dans le document. La valeur par défaut est True.


**Returns:**
booléen
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Si AutoFontSubstitution est désactivé, GroupDocs.Conversion utilise DefaultFont pour la substitution des polices manquantes. Si AutoFontSubstitution est activé,
GroupDocs.Conversion évalue tous les champs associés dans FontInfo (Panose, Sig, etc.) pour la police manquante et trouve la correspondance la plus proche parmi les sources de polices disponibles.
Notez que le mécanisme de substitution de police remplacera DefaultFont dans les cas où FontInfo pour la police manquante est disponible dans le document. La valeur par défaut est True.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Remplace les polices spécifiques lors de la conversion d'un document Words.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Si EmbedTrueTypeFonts est vrai, GroupDocs.Conversion intègre les polices TrueType dans le document de sortie. Valeur par défaut : false.


**Returns:**
booléen
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| embedTrueTypeFonts | booléen |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Met à jour la mise en page après le chargement. Valeur par défaut : false.


**Returns:**
booléen
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| updatePageLayout | booléen |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Met à jour les champs après le chargement. Valeur par défaut : false.


**Returns:**
booléen
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| updateFields | booléen |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Conserve la valeur originale du champ date. Valeur par défaut : false.


**Returns:**
booléen
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Définit la conservation de la valeur originale du champ date.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| keepDateFieldOriginalValue | booléen |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Remplace les polices spécifiques lors de la conversion d'un document Words.


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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Masquer le balisage et le suivi des modifications pour les documents Word.


**Returns:**
booléen
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Masquer le balisage et le suivi des modifications pour les documents Word.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Masquer les commentaires.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Options des signets


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Options des signets


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Spécifie s’il faut conserver les champs de formulaire Microsoft Word en tant que champs de formulaire dans le PDF ou les convertir en texte. La valeur par défaut est false.


**Returns:**
booléen - drapeau preserveFontFields

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Définit le drapeau preserveFontFields


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | preserveFontFields | booléen | conserver les champs de formulaire Microsoft Word en tant que champs de formulaire dans le PDF ou les convertir en texte |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Spécifie s’il faut utiliser un formateur de texte pour un meilleur affichage du crénage. La valeur par défaut est false.


**Returns:**
booléen
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Spécifie s’il faut utiliser un formateur de texte pour un meilleur affichage du crénage. La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | isUseTextShaper | booléen | drapeau isUseTextShaper |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Détermine si la structure du document doit être conservée lors de la conversion en PDF (la valeur par défaut est false). Notez que l'exportation de la structure du document augmente considérablement la consommation de mémoire, en particulier pour les gros documents.


**Returns:**
booléen
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| preserveDocumentStructure | booléen |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Si true toutes les ressources externes ne seront pas chargées, à l'exception des ressources dans le


**Returns:**
booléen
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| skip | booléen |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Ressources externes qui seront toujours chargées


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Spécifie comment les commentaires doivent être affichés dans le document de sortie. La valeur par défaut est ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Afficher le nom complet du commentateur dans les commentaires. La valeur par défaut est false.


**Returns:**
booléen
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| showFullCommenterName | booléen |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Activer ou désactiver la génération de la numérotation des pages dans le document converti. Valeur par défaut : false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Obtient les options de césure pour les documents WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Définit les options de césure pour les documents WordProcessing.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Obtient le drapeau InterruptThreadIfImageExceptionThrown. Valeur par défaut : false. Si vrai, interrompt le thread principal de conversion lorsqu’une exception dans un thread de traitement d’image s’est produite.


**Returns:**
booléen
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Définit le drapeau InterruptThreadIfImageExceptionThrown.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | booléen |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Lorsqu’il est activé (par défaut), les paragraphes et les runs dont le texte est majoritairement de droite à gauche (RTL) verront leurs drapeaux bidi réparés avant la conversion.


Cela correspond à l'heuristique appliquée par Microsoft Word et LibreOffice et
corrige le rendu des documents arabes/hébreux générés par des générateurs
(notamment Google Docs) qui émettent OOXML sans


et avec

sur les séquences contenant uniquement du texte RTL.


Définir sur
false
pour préserver une interprétation stricte d'OOXML du
balisage source.


**Returns:**
booléen
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Définit autoDetectRtlDirection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | autoDetectRtlDirection | booléen | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtient l'option permettant de contrôler si le conteneur du document doit être converti


**Returns:**
booléen
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwner | booléen |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option pour contrôler si les documents possédés dans le conteneur de documents doivent être convertis


**Returns:**
booléen
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwned | booléen |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option pour contrôler le nombre de niveaux de profondeur à convertir


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| depth | int |  |

