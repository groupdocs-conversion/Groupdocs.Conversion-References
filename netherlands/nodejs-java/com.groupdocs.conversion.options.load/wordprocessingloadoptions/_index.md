---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van WordProcessing-documenten."
type: docs
weight: 44
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Opties voor het laden van WordProcessing-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor Words-document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor Words-document. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Als AutoFontSubstitution is uitgeschakeld, gebruikt GroupDocs.Conversion het DefaultFont voor het vervangen van ontbrekende lettertypen. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Als AutoFontSubstitution is uitgeschakeld, gebruikt GroupDocs.Conversion het DefaultFont voor het vervangen van ontbrekende lettertypen. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Vervang specifieke lettertypen bij het converteren van een Words-document. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Als EmbedTrueTypeFonts true is, embedt GroupDocs.Conversion TrueType-lettertypen in het uitvoerdocument. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | Werk de paginalay-out bij na het laden. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | Werk velden bij na het laden. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Behoud de oorspronkelijke waarde van het datumveld. |
| [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Stelt in om de oorspronkelijke waarde van het datumveld te behouden. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Vervang specifieke lettertypen bij het converteren van een Words-document. |
| [getPassword()](#getPassword--) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Verberg opmaak en wijzigingsbijhouden voor Word-documenten. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Verberg opmaak en wijzigingsbijhouden voor Word-documenten. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Verberg opmerkingen. |
| [getBookmarkOptions()](#getBookmarkOptions--) | Bladwijzeropties |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Bladwijzeropties |
| [isPreserveFontFields()](#isPreserveFontFields--) | Specificeert of Microsoft Word-formuliervelden behouden moeten blijven als formuliervelden in PDF of geconverteerd moeten worden naar tekst. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Stelt de preserveFontFields-vlag in |
| [isUseTextShaper()](#isUseTextShaper--) | Specificeert of een tekstvormer moet worden gebruikt voor een betere kerning-weergave. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Specificeert of een tekstvormer moet worden gebruikt voor een betere kerning-weergave. |
| [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Bepaalt of de documentstructuur behouden moet blijven bij het converteren naar PDF (standaard is false). |
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
| [getCommentDisplayMode()](#getCommentDisplayMode--) | Specificeert hoe opmerkingen moeten worden weergegeven in het uitvoerdocument. |
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
| [getShowFullCommenterName()](#getShowFullCommenterName--) | Toon volledige naam van de commentator in opmerkingen. |
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).

### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor Words-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor Words-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Als AutoFontSubstitution is uitgeschakeld, gebruikt GroupDocs.Conversion de DefaultFont voor de vervanging van ontbrekende lettertypen. Als AutoFontSubstitution is ingeschakeld, evalueert GroupDocs.Conversion alle gerelateerde velden in FontInfo (Panose, Sig enz.) voor het ontbrekende lettertype en vindt de dichtstbijzijnde overeenkomst onder de beschikbare lettertypebronnen. Merk op dat het mechanisme voor lettertypevervanging de DefaultFont zal overschrijven in gevallen waarin FontInfo voor het ontbrekende lettertype beschikbaar is in het document. De standaardwaarde is True.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Als AutoFontSubstitution is uitgeschakeld, gebruikt GroupDocs.Conversion de DefaultFont voor de vervanging van ontbrekende lettertypen. Als AutoFontSubstitution is ingeschakeld, evalueert GroupDocs.Conversion alle gerelateerde velden in FontInfo (Panose, Sig enz.) voor het ontbrekende lettertype en vindt de dichtstbijzijnde overeenkomst onder de beschikbare lettertypebronnen. Merk op dat het mechanisme voor lettertypevervanging de DefaultFont zal overschrijven in gevallen waarin FontInfo voor het ontbrekende lettertype beschikbaar is in het document. De standaardwaarde is True.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Vervang specifieke lettertypen bij het converteren van een Words-document.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Als EmbedTrueTypeFonts true is, embedt GroupDocs.Conversion TrueType-lettertypen in het uitvoerdocument. Standaard: false

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Werk paginalay-out bij na het laden. Standaard: false

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Werk velden bij na het laden. Standaard: false

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Behoud de oorspronkelijke waarde van het datumveld. Standaard: false

**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Stelt in om de oorspronkelijke waarde van het datumveld te behouden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Vervang specifieke lettertypen bij het converteren van een Words-document.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Verberg opmaak en wijzigingsbijhouden voor Word-documenten.

**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Verberg opmaak en wijzigingsbijhouden voor Word-documenten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Verberg opmerkingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Bladwijzeropties

**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Bladwijzeropties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Specificeert of Microsoft Word-formuliervelden behouden moeten blijven als formuliervelden in PDF of geconverteerd moeten worden naar tekst. Standaard is false.

**Returns:**
boolean - preserveFontFields vlag
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Stelt de preserveFontFields-vlag in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| preserveFontFields | boolean | Behoud Microsoft Word-formuliervelden als formuliervelden in PDF of converteer ze naar tekst |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Specificeert of een tekstvormer moet worden gebruikt voor een betere kerning-weergave. Standaard is false.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Specificeert of een tekstvormer moet worden gebruikt voor een betere kerning-weergave. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isUseTextShaper | boolean | isUseTextShaper vlag |

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Bepaalt of de documentstructuur behouden moet blijven bij het converteren naar PDF (standaard is false). Merk op dat het exporteren van de documentstructuur het geheugenverbruik aanzienlijk verhoogt, vooral bij grote documenten.

**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Als true, worden alle externe bronnen niet geladen, met uitzondering van de bronnen in de

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Externe bronnen die altijd worden geladen

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Specificeert hoe opmerkingen moeten worden weergegeven in het uitvoerdocument. Standaard is ShowInBalloons.

**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Toon volledige naam van de commentator in opmerkingen. Standaard is false.

**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

