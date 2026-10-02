---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "WordProcessing 中处理书签的选项"
type: docs
weight: 39
url: /zh/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

WordProcessing 中处理书签的选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | 指定在文档大纲中显示 Word 书签的默认级别。 |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | 指定在文档大纲中显示 Word 书签的默认级别。 |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | 指定在文档大纲中包含多少级标题（使用标题样式格式化的段落）。 |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | 指定在文档大纲中包含多少级标题（使用标题样式格式化的段落）。 |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | 指定在查看文件时文档大纲展开的级别数量。 |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | 指定在查看文件时文档大纲展开的级别数量。 |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


指定在文档大纲中显示 Word 书签的默认级别。默认值为 0。有效范围为 0 到 9。


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


指定在文档大纲中显示 Word 书签的默认级别。默认值为 0。有效范围为 0 到 9。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


指定在文档大纲中包含多少级标题（使用标题样式格式化的段落）。默认值为 0。有效范围为 0 到 9。


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


指定在文档大纲中包含多少级标题（使用标题样式格式化的段落）。默认值为 0。有效范围为 0 到 9。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


指定在查看文件时文档大纲展开的级别数量。默认值为 0。有效范围为 0 到 9。注意，此选项在保存为 XPS 时无效。


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


指定在查看文件时文档大纲展开的级别数量。默认值为 0。有效范围为 0 到 9。注意，此选项在保存为 XPS 时无效。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

