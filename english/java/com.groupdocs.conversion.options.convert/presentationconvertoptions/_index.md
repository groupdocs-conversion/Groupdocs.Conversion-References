---
title: PresentationConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Describes options for conversion to Presentation file type.
type: docs
weight: 32
url: /java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Describes options for conversion to Presentation file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationConvertOptions()](#PresentationConvertOptions--) | Initializes new instance of [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Set this property if you want to protect the converted document with a password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set this property if you want to protect the converted document with a password. |
| [getZoom()](#getZoom--) | Specifies the zoom level in percentage. |
| [setZoom(int value)](#setZoom-int-) | Specifies the zoom level in percentage. |
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Initializes new instance of [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) class.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Set this property if you want to protect the converted document with a password.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Set this property if you want to protect the converted document with a password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specifies the zoom level in percentage. Default is 100. Default zoom is supported till Microsoft Powerpoint 2010. Starting from Microsoft Powerpoint 2013 default zoom is no longer set to document, instead it appears to use the zoom factor of the last document that was opened.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifies the zoom level in percentage. Default is 100. Default zoom is supported till Microsoft Powerpoint 2010. Starting from Microsoft Powerpoint 2013 default zoom is no longer set to document, instead it appears to use the zoom factor of the last document that was opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

