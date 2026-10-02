---
title: "IPagedConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示通过指定起始页和页数来限制页面的转换选项"
type: docs
weight: 55
url: /zh/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

表示通过指定起始页和页数来限制页面的转换选项

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 获取开始转换的页码。 |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | 设置开始转换的页码。 |
|
|  | [getPagesCount()](#getPagesCount--) | 获取从 PageNumber 开始要转换的页数。 |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | 设置从 PageNumber 开始要转换的页数。 |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


获取开始转换的页码。


**Returns:**
java.lang.Integer - 开始转换的页码。

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


设置开始转换的页码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageNumber | int | 开始转换的页码。 |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


获取从 PageNumber 开始要转换的页数。


**Returns:**
java.lang.Integer - 从 PageNumber 开始要转换的页数。

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


设置从 PageNumber 开始要转换的页数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pagesCount | int | 从 PageNumber 开始要转换的页数。 |
|

