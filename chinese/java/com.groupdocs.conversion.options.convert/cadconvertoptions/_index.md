---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "转换为 Cad 类型的选项。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

转换为 Cad 类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | 初始化类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


初始化类的新实例。


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


获取开始转换的页码。


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


设置开始转换的页码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


获取从 PageNumber 开始要转换的页数。


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


设置从 PageNumber 开始要转换的页数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pagesCount | int |  |

