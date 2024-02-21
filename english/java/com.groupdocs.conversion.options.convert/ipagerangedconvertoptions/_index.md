---
title: IPageRangedConvertOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Represents convert options that support conversion of specific list of pages
type: docs
weight: 52
url: /nodejs-java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Represents convert options that support conversion of specific list of pages
## Methods

| Method | Description |
| --- | --- |
| [getPages()](#getPages--) | Gets The list of page indexes to be converted. |
| [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Sets the list of page indexes to be converted. |
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Gets The list of page indexes to be converted. Should be specified to convert specific pages.

**Returns:**
java.util.List<java.lang.Integer> - The list of page indexes to be converted. Should be specified to convert specific pages.
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Sets the list of page indexes to be converted. Should be specified to convert specific pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | java.util.List<java.lang.Integer> | The list of page indexes to be converted. Should be specified to convert specific pages. |

