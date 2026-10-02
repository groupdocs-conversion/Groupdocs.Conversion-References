---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 Mbox 文档的选项。"
type: docs
weight: 23
url: /zh/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

加载 Mbox 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | 初始化类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | 所有者将不会被转换 |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} 默认：3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


初始化类的新实例。


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


所有者将不会被转换


**Returns:**
布尔
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


选项，用于控制文档容器中的所属文档是否必须转换


**Returns:**
布尔
### getDepth() {#getDepth--}
```
public int getDepth()
```


控制执行转换的深度级别数量的选项 默认：3


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| depth | int |  |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
