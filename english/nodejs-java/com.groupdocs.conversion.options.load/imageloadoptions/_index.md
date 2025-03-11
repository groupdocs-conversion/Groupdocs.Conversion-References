---
title: ImageLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading Image documents.
type: docs
weight: 23
url: /nodejs-java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Options for loading Image documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageLoadOptions()](#ImageLoadOptions--) | Initializes new instance of [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Default font for Psd, Emf, Wmf document types. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for Psd, Emf, Wmf document types. |
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
| [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Set image OCR connector |
| [getResetFontFolders()](#getResetFontFolders--) | Reset font folders before loading document |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Initializes new instance of [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) class.

### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Input document file type

**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Default font for Psd, Emf, Wmf document types. The following font will be used if a font is missing.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for Psd, Emf, Wmf document types. The following font will be used if a font is missing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
boolean
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


Set image OCR connector

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR connector instance |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset font folders before loading document

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

