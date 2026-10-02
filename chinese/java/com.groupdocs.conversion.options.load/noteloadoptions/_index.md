---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 One 文档的选项。"
type: docs
weight: 24
url: /zh/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

加载 One 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | 初始化 [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Note 文档的默认字体。 |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Note 文档的默认字体。 |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | 在转换 Note 文档时替换特定字体。 |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | 在转换 Note 文档时替换特定字体。 |
|
|  | [getPassword()](#getPassword--) | 设置密码以解除受保护文档的保护。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置密码以解除受保护文档的保护。 |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


初始化 [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


输入文档文件类型


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Note 文档的默认字体。如果缺少字体，将使用以下字体。


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Note 文档的默认字体。如果缺少字体，将使用以下字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


在转换 Note 文档时替换特定字体。


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


在转换 Note 文档时替换特定字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


设置密码以解除受保护文档的保护。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置密码以解除受保护文档的保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

