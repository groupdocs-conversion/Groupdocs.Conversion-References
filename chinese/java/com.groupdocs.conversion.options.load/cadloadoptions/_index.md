---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 CAD 文档的选项。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

加载 CAD 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | 初始化 [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | 指定要转换的 CAD 布局 |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | 指定要转换的 CAD 布局 |
|
|  | [getDrawType()](#getDrawType--) | 获取绘图类型。 |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | 设置绘图类型。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | 设置背景颜色。 |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | 获取 CTB 源。 |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | 设置 CTB 源。 |
|
|  | [getDrawColor()](#getDrawColor--) | 获取前景颜色。 |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | 设置前景颜色。 |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


初始化 [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


输入文档文件类型


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


指定要转换的 CAD 布局


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


指定要转换的 CAD 布局


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


获取绘图类型。


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


设置绘图类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


获取背景颜色。


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


设置背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


获取 CTB 源。


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


设置 CTB 源。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


获取前景颜色。


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


设置前景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

