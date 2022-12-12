---
title: SpreadsheetConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for conversion to Spreadsheet file type.
type: docs
weight: 39
url: /java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Options for conversion to Spreadsheet file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Initializes new instance of [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Set this property if you want to protect the converted document with a password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set this property if you want to protect the converted document with a password. |
| [getZoom()](#getZoom--) | Specifies the zoom level in percentage. |
| [setZoom(int value)](#setZoom-int-) | Specifies the zoom level in percentage. |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Initializes new instance of [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) class.

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


Specifies the zoom level in percentage. Default is 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifies the zoom level in percentage. Default is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

