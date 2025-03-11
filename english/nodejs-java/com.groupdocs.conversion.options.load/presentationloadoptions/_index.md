---
title: PresentationLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading Presentation documents.
type: docs
weight: 33
url: /nodejs-java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Options for loading Presentation documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) | Initializes new instance of [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Default font for rendering the presentation. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for rendering the presentation. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Substitute specific fonts when converting Presentation document. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Substitute specific fonts when converting Presentation document. |
| [getPassword()](#getPassword--) | Set password to unprotect protected document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set password to unprotect protected document. |
| [getHideComments()](#getHideComments--) | Hide comments. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Hide comments. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Show hidden slides. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Show hidden slides. |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
| [getNotesPosition()](#getNotesPosition--) | Represents the way comments are printed with the slide. |
| [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | Represents the way notes are printed with the slide. |
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


Initializes new instance of [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) class.

### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


Input document file type

**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Default font for rendering the presentation. The following font will be used if a presentation font is missing.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for rendering the presentation. The following font will be used if a presentation font is missing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Substitute specific fonts when converting Presentation document.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Substitute specific fonts when converting Presentation document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Set password to unprotect protected document.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Set password to unprotect protected document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Hide comments.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Hide comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Show hidden slides.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Show hidden slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


If true all external resource will not be loading with exception of the resources in the

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


External resources that will be always loaded

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


Represents the way comments are printed with the slide. Default is None.

**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


Represents the way notes are printed with the slide. Default is None.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

