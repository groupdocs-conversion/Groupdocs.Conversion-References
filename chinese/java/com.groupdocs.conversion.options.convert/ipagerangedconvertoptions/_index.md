---
title: "IPageRangedConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示支持特定页面列表转换的转换选项"
type: docs
weight: 52
url: /zh/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

表示支持特定页面列表转换的转换选项

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPages()](#getPages--) | 获取要转换的页面索引列表。 |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | 设置要转换的页面索引列表。 |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


获取要转换的页面索引列表。应指定以转换特定页面。


**Returns:**
java.util.List<java.lang.Integer> - 要转换的页面索引列表。应指定以转换特定页面。

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


设置要转换的页面索引列表。应指定以转换特定页面。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 页面 | java.util.List<java.lang.Integer> | 要转换的页面索引列表。应指定以转换特定页面。 |
|

