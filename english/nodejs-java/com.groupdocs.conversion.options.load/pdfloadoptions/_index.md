---
title: PdfLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading Pdf documents.
type: docs
weight: 27
url: /nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Options for loading Pdf documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Initializes new instance of [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Remove embedded files. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Remove embedded files. |
| [getPassword()](#getPassword--) | Set password to unprotect protected document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set password to unprotect protected document. |
| [getDefaultFont()](#getDefaultFont--) | Default font for Pdf document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for Pdf document. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Substitute specific fonts when converting Pdf document. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Substitute specific fonts when converting Pdf document. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Hide annotations in Pdf documents. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Hide annotations in Pdf documents. |
| [getFlattenAllFields()](#getFlattenAllFields--) | Flatten all the fields of the PDF form. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Flatten all the fields of the PDF form. |
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


Default font for Pdf document. The following font will be used if a font is missing.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for Pdf document. The following font will be used if a font is missing.

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

