---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载图表文档的选项。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

加载图表文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | 初始化 [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Diagram 文档的默认字体。 |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Diagram 文档的默认字体。 |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


初始化 [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


输入文档文件类型


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Diagram 文档的默认字体。如果缺少字体，将使用以下字体。


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Diagram 文档的默认字体。如果缺少字体，将使用以下字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

