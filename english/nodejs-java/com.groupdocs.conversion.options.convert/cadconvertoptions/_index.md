---
title: CadConvertOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for conversion to Cad type.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Options for conversion to Cad type.
## Constructors

| Constructor | Description |
| --- | --- |
| [CadConvertOptions()](#CadConvertOptions--) | Initializes new instance of  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Initializes new instance of  class.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Gets the page number to start conversion from.

**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Sets the page number to start conversion from.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Gets number of pages to convert starting from PageNumber.

**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Sets number of pages to convert starting from PageNumber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pagesCount | int |  |

