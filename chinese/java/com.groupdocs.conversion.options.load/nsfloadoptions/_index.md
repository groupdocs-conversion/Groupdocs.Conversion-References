---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 Nsf 文档的选项。"
type: docs
weight: 25
url: /zh/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

加载 Nsf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


获取选项以控制文档容器本身是否必须转换


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


选项，用于控制转换的深度层级数


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

