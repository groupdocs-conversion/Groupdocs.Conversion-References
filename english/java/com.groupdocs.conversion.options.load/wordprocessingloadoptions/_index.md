---
title: WordProcessingLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading WordProcessing documents.
type: docs
weight: 33
url: /java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable
```

Options for loading WordProcessing documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Initializes new instance of [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Default font for Words document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for Words document. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Substitute specific fonts when converting Words document. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | If EmbedTrueTypeFonts is true, GroupDocs.Conversion embed true type fonts in the output document. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | Update page layout after loading. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | Update fields after loading. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Substitute specific fonts when converting Words document. |
| [getPassword()](#getPassword--) | Set password to unprotect protected document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set password to unprotect protected document. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Hide markup and track changes for Word documents. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Hide markup and track changes for Word documents. |
| [getHideComments()](#getHideComments--) | Hide comments. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Hide comments. |
| [getBookmarkOptions()](#getBookmarkOptions--) | Bookmarks options |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Bookmarks options |
| [isPreserveFontFields()](#isPreserveFontFields--) | Specifies whether to preserve Microsoft Word form fields as form fields in PDF or convert them to text. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Sets preserveFontFields flag |
| [isUseTextShaper()](#isUseTextShaper--) | Specifies whether to use a text shaper for better kerning display. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Specifies whether to use a text shaper for better kerning display. |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Initializes new instance of [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) class.

### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Input document file type

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Default font for Words document. The following font will be used if a font is missing.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for Words document. The following font will be used if a font is missing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. If AutoFontSubstitution is enabled, GroupDocs.Conversion evaluates all the related fields in FontInfo (Panose, Sig etc) for the missing font and finds the closest match among the available font sources. Note that font substitution mechanism will override the DefaultFont in cases when FontInfo for the missing font is available in the document. The default value is True.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. If AutoFontSubstitution is enabled, GroupDocs.Conversion evaluates all the related fields in FontInfo (Panose, Sig etc) for the missing font and finds the closest match among the available font sources. Note that font substitution mechanism will override the DefaultFont in cases when FontInfo for the missing font is available in the document. The default value is True.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Substitute specific fonts when converting Words document.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


If EmbedTrueTypeFonts is true, GroupDocs.Conversion embed true type fonts in the output document. Default: false

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Update page layout after loading. Default: false

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Update fields after loading. Default: false

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateFields | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Substitute specific fonts when converting Words document.

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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Hide markup and track changes for Word documents.

**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Hide markup and track changes for Word documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Bookmarks options

**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Bookmarks options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Specifies whether to preserve Microsoft Word form fields as form fields in PDF or convert them to text. Default is false.

**Returns:**
boolean - preserveFontFields flag
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Sets preserveFontFields flag

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| preserveFontFields | boolean | preserve Microsoft Word form fields as form fields in PDF or convert them to text |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Specifies whether to use a text shaper for better kerning display. Default is false.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Specifies whether to use a text shaper for better kerning display. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isUseTextShaper | boolean | isUseTextShaper flag |

