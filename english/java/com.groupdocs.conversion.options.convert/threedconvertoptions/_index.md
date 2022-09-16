---
title: ThreeDConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: 
type: docs
weight: 41
url: /java/com.groupdocs.conversion.options.convert/threedconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class ThreeDConvertOptions extends ConvertOptions<ThreeDFileType> implements IPagedConvertOptions
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ThreeDConvertOptions()](#ThreeDConvertOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### ThreeDConvertOptions() {#ThreeDConvertOptions--}
```
public ThreeDConvertOptions()
```


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

