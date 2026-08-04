---
title: PdfLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Pdf documents.
type: docs
weight: 27
url: /java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Options for loading Pdf documents.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Initializes new instance of [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) class.
 |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Remove embedded files.
 |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Remove embedded files.
 |
| [getPassword()](#getPassword--) | Set password to unprotect protected document.
 |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set password to unprotect protected document.
 |
| [getDefaultFont()](#getDefaultFont--) | Default font for Pdf document.
 |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for Pdf document.
 |
| [getFontSubstitutes()](#getFontSubstitutes--) | Substitute specific fonts when converting Pdf document.
 |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Substitute specific fonts when converting Pdf document.
 |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Hide annotations in Pdf documents.
 |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Hide annotations in Pdf documents.
 |
| [getFlattenAllFields()](#getFlattenAllFields--) | Flatten all the fields of the PDF form.
 |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Flatten all the fields of the PDF form.
 |
| [getResetFontFolders()](#getResetFontFolders--) | Reset font folders before loading document.
 |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [isPageNumbering()](#isPageNumbering--) | Enable or disable generation of page numbering in converted document.
 |
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
| [isRemoveJavascript()](#isRemoveJavascript--) | Gets the Remove JavaScript flag.
 |
| [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Sets the Remove JavaScript flag.
 |
| [isConvertOwner()](#isConvertOwner--) | Specifies whether the owner document should be converted.
 |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Specifies whether the owner document should be converted.
 |
| [isConvertOwned()](#isConvertOwned--) | Specifies whether owned documents should be converted.
 |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Specifies whether owned documents should be converted.
 |
| [getDepth()](#getDepth--) | Maximum depth for processing owned documents.
 |
| [setDepth(int depth)](#setDepth-int-) | Maximum depth for processing owned documents.
 |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Initializes new instance of [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) class.


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Input document file type


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Remove embedded files.


**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Remove embedded files.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Default font for Pdf document.
The following font will be used if a font is missing.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for Pdf document.
The following font will be used if a font is missing.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Substitute specific fonts when converting Pdf document.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Substitute specific fonts when converting Pdf document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Hide annotations in Pdf documents.


**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Hide annotations in Pdf documents.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Flatten all the fields of the PDF form.


**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Flatten all the fields of the PDF form.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset font folders before loading document.


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Enable or disable generation of page numbering in converted document. Default: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Gets the Remove JavaScript flag.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Sets the Remove JavaScript flag.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Specifies whether the owner document should be converted.

Default is 
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Specifies whether the owner document should be converted.

Default is 
true
.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Specifies whether owned documents should be converted.

Default is 
false
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Specifies whether owned documents should be converted.

Default is 
false
.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Maximum depth for processing owned documents.

Default is 
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Maximum depth for processing owned documents.

Default is 
2
.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| depth | int |  |

