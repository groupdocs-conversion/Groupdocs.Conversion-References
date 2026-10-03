---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för att läsa in presentationsdokument."
type: docs
weight: 29
url: /sv/java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IDocumentsContainerLoadOptions
```

Alternativ för att läsa in presentationsdokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationLoadOptions()](#PresentationLoadOptions--) | Initierar en ny instans av klassen [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för rendering av presentationen. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för rendering av presentationen. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ersätt specifika teckensnitt när ett Presentation-dokument konverteras. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ersätt specifika teckensnitt när ett Presentation-dokument konverteras. |
|
|  | [getPassword()](#getPassword--) | Ange lösenord för att avskydda skyddat dokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ange lösenord för att avskydda skyddat dokument. |
|
|  | [getHideComments()](#getHideComments--) | Dölj kommentarer. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Dölj kommentarer. |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Visa dolda bilder. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Visa dolda bilder. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
|  | [getNotesPosition()](#getNotesPosition--) | Representerar hur kommentarer skrivs ut med bilden. |
|
|  | [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | Representerar hur anteckningar skrivs ut med bilden. |
|
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


Initierar en ny instans av klassen [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


Dokumentfiltyp för inmatning


**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för rendering av presentationen. Följande teckensnitt kommer att användas om ett presentations‑teckensnitt saknas.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för rendering av presentationen. Följande teckensnitt kommer att användas om ett presentations‑teckensnitt saknas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ersätt specifika teckensnitt när ett Presentation-dokument konverteras.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ersätt specifika teckensnitt när ett Presentation-dokument konverteras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Dölj kommentarer.


**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Dölj kommentarer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Visa dolda bilder.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Visa dolda bilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Om true kommer alla externa resurser inte att laddas med undantag för resurserna i


**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Externa resurser som alltid kommer att laddas


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getDocumentFontSources() {#getDocumentFontSources--}
```
public List<String> getDocumentFontSources()
```




**Returns:**
java.util.List<java.lang.String>
### setDocumentFontSources(List<String> documentFontSources) {#setDocumentFontSources-java.util.List-java.lang.String--}
```
public void setDocumentFontSources(List<String> documentFontSources)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


Representerar hur kommentarer skrivs ut med bilden. Standard är Ingen.


**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


Representerar hur anteckningar skrivs ut med bilden. Standard är Ingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| notesPosition | [PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition) |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public PresentationCommentsPosition getCommentsPosition()
```




**Returns:**
[PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) - 
### setCommentsPosition(PresentationCommentsPosition commentsPosition) {#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-}
```
public void setCommentsPosition(PresentationCommentsPosition commentsPosition)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Hämtar alternativ för att styra om dokumentbehållaren själv måste konverteras


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Alternativ för att styra om de ägda dokumenten i dokumentbehållaren måste konverteras


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Alternativ för att styra hur många nivåer i djupet konverteringen ska utföras


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| depth | int |  |

