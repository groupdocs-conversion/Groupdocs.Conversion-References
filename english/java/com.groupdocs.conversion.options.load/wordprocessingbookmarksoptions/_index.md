---
title: WordProcessingBookmarksOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for handling bookmarks in WordProcessing
type: docs
weight: 32
url: /java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Options for handling bookmarks in WordProcessing
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Specifies the default level in the document outline at which to display Word bookmarks. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Specifies the default level in the document outline at which to display Word bookmarks. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Specifies how many levels of headings (paragraphs formatted with the Heading styles) to include in the document outline. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Specifies how many levels of headings (paragraphs formatted with the Heading styles) to include in the document outline. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Specifies how many levels in the document outline to show expanded when the file is viewed. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Specifies how many levels in the document outline to show expanded when the file is viewed. |
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Specifies the default level in the document outline at which to display Word bookmarks. Default is 0. Valid range is 0 to 9.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Specifies the default level in the document outline at which to display Word bookmarks. Default is 0. Valid range is 0 to 9.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Specifies how many levels of headings (paragraphs formatted with the Heading styles) to include in the document outline. Default is 0. Valid range is 0 to 9.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Specifies how many levels of headings (paragraphs formatted with the Heading styles) to include in the document outline. Default is 0. Valid range is 0 to 9.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Specifies how many levels in the document outline to show expanded when the file is viewed. Default is 0. Valid range is 0 to 9. Note that this options will not work when saving to XPS.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Specifies how many levels in the document outline to show expanded when the file is viewed. Default is 0. Valid range is 0 to 9. Note that this options will not work when saving to XPS.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

