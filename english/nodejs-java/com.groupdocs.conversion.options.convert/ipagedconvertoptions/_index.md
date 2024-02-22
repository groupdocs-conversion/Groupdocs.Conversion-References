---
title: IPagedConvertOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Represents convert options that allows conversion to perform page limitation by specifying start page and pages count
type: docs
weight: 54
url: /nodejs-java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Represents convert options that allows conversion to perform page limitation by specifying start page and pages count
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Gets the page number to start conversion from. |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) | Sets the page number to start conversion from. |
| [getPagesCount()](#getPagesCount--) | Gets number of pages to convert starting from PageNumber. |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) | Sets number of pages to convert starting from PageNumber. |
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Gets the page number to start conversion from.

**Returns:**
java.lang.Integer - The page number to start conversion from.
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Sets the page number to start conversion from.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number to start conversion from. |

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Gets number of pages to convert starting from PageNumber.

**Returns:**
java.lang.Integer - Number of pages to convert starting from PageNumber.
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Sets number of pages to convert starting from PageNumber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pagesCount | int | Number of pages to convert starting from PageNumber. |

