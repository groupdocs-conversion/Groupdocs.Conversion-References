---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 Pdf 文档的选项。"
type: docs
weight: 27
url: /zh/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

加载 Pdf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | 初始化 [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | 移除嵌入的文件。 |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | 移除嵌入的文件。 |
|
|  | [getPassword()](#getPassword--) | 设置密码以解除受保护文档的保护。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置密码以解除受保护文档的保护。 |
|
|  | [getDefaultFont()](#getDefaultFont--) | Pdf 文档的默认字体。 |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pdf 文档的默认字体。 |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | 在转换 Pdf 文档时替换特定字体。 |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | 在转换 Pdf 文档时替换特定字体。 |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | 隐藏 Pdf 文档中的注释。 |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | 隐藏 Pdf 文档中的注释。 |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | 将 PDF 表单的所有字段扁平化。 |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | 将 PDF 表单的所有字段扁平化。 |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | 在加载文档之前重置字体文件夹。 |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | 启用或禁用在转换后文档中生成页码。 |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | 获取 Remove JavaScript 标志。 |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | 设置 Remove JavaScript 标志。 |
|
|  | [isConvertOwner()](#isConvertOwner--) | 指定是否应转换所有者文档。 |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | 指定是否应转换所有者文档。 |
|
|  | [isConvertOwned()](#isConvertOwned--) | 指定是否应转换所属文档。 |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | 指定是否应转换所属文档。 |
|
|  | [getDepth()](#getDepth--) | 处理所属文档的最大深度。 |
|
|  | [setDepth(int depth)](#setDepth-int-) | 处理所属文档的最大深度。 |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


初始化 [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


输入文档文件类型


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


移除嵌入的文件。


**Returns:**
布尔
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


移除嵌入的文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Pdf 文档的默认字体。
如果缺少字体，将使用以下字体。


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Pdf 文档的默认字体。
如果缺少字体，将使用以下字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


在转换 Pdf 文档时替换特定字体。


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


在转换 Pdf 文档时替换特定字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


隐藏 Pdf 文档中的注释。


**Returns:**
布尔
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


隐藏 Pdf 文档中的注释。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


将 PDF 表单的所有字段扁平化。


**Returns:**
布尔
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


将 PDF 表单的所有字段扁平化。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


在加载文档之前重置字体文件夹。


**Returns:**
布尔
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resetFontFolders | 布尔 |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


在转换的文档中启用或禁用页码生成。默认值：false。


**Returns:**
布尔
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isPageNumbering | 布尔 |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


获取 Remove JavaScript 标志。


**Returns:**
布尔
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


设置 Remove JavaScript 标志。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeJavascript | 布尔 |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


指定是否应转换所有者文档。

默认是
true
.


**Returns:**
布尔
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


指定是否应转换所有者文档。

默认是
true
.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwner | 布尔 |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


指定是否应转换所属文档。

默认是
false
.


**Returns:**
布尔
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


指定是否应转换所属文档。

默认是
false
.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwned | 布尔 |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


处理所属文档的最大深度。

默认是
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


处理所属文档的最大深度。

默认是
2
.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| depth | int |  |

