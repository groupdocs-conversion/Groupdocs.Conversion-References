---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载个人存储文档的选项。"
type: docs
weight: 28
url: /zh/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

加载个人存储文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | 初始化类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFolder()](#getFolder--) | 要处理的文件夹，默认是 Inbox |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | 设置要处理的文件夹 |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} 所有者将不会被转换 |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


初始化类的新实例。


### getFolder() {#getFolder--}
```
public String getFolder()
```


要处理的文件夹，默认是 Inbox


**Returns:**
java.lang.String - 要处理的文件夹

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


设置要处理的文件夹


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件夹 | java.lang.String | 文件夹 |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


获取用于控制文档容器本身是否必须转换的选项。所有者将不会被转换


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

