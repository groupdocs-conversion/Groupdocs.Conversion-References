---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 WordProcessing 文档的选项。"
type: docs
weight: 40
url: /zh/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

加载 WordProcessing 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | 初始化 [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Words 文档的默认字体。 |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Words 文档的默认字体。 |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | 如果已禁用 AutoFontSubstitution，GroupDocs.Conversion 将使用 DefaultFont 来替代缺失的字体。 |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | 如果已禁用 AutoFontSubstitution，GroupDocs.Conversion 将使用 DefaultFont 来替代缺失的字体。 |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | 在转换 Words 文档时替换特定字体。 |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | 如果 EmbedTrueTypeFonts 为 true，GroupDocs.Conversion 会在输出文档中嵌入 TrueType 字体。 |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | 加载后更新页面布局。 |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | 加载后更新字段。 |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | 保留日期字段的原始值。 |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | 设置保留日期字段的原始值。 |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | 在转换 Words 文档时替换特定字体。 |
|
|  | [getPassword()](#getPassword--) | 设置密码以解除受保护文档的保护。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置密码以解除受保护文档的保护。 |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | 隐藏 Word 文档的标记和修订痕迹。 |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | 隐藏 Word 文档的标记和修订痕迹。 |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | 隐藏批注。 |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | 书签选项 |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | 书签选项 |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | 指定是将 Microsoft Word 表单字段在 PDF 中保留为表单字段，还是将其转换为文本。 |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | 设置 preserveFontFields 标志 |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | 指定是否使用文本整形器以获得更好的字距显示。 |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | 指定是否使用文本整形器以获得更好的字距显示。 |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | 确定在转换为 PDF 时是否应保留文档结构（默认值为 false）。 |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | 指定在输出文档中如何显示批注。 |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | 在批注中显示完整的评论者姓名。 |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | 启用或禁用在转换后文档中生成页码。 |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | 获取 WordProcessing 文档的连字符选项。 |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | 设置 WordProcessing 文档的连字符选项。 |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | 获取 InterruptThreadIfImageExceptionThrown 标志，默认值：false。如果为 true，则在图像处理线程出现异常时中断主转换线程。 |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | 设置 InterruptThreadIfImageExceptionThrown 标志 |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | 启用后（默认），文本主要为从右到左（RTL）的段落和运行将在转换前修复其双向标志。 |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | 设置 autoDetectRtlDirection |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


初始化 [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


输入文档文件类型


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Words 文档的默认字体。如果缺少字体，将使用以下字体。


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Words 文档的默认字体。如果缺少字体，将使用以下字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


如果 AutoFontSubstitution 被禁用，GroupDocs.Conversion 使用 DefaultFont 来替代缺失的字体。如果 AutoFontSubstitution 被启用，
GroupDocs.Conversion 评估 FontInfo 中的所有相关字段（Panose、Sig 等），以查找缺失字体，并在可用的字体源中找到最接近的匹配。
请注意，当文档中提供了缺失字体的 FontInfo 时，字体替代机制将覆盖 DefaultFont。默认值为 True。


**Returns:**
布尔
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


如果 AutoFontSubstitution 被禁用，GroupDocs.Conversion 使用 DefaultFont 来替代缺失的字体。如果 AutoFontSubstitution 被启用，
GroupDocs.Conversion 评估 FontInfo 中的所有相关字段（Panose、Sig 等），以查找缺失字体，并在可用的字体源中找到最接近的匹配。
请注意，当文档中提供了缺失字体的 FontInfo 时，字体替代机制将覆盖 DefaultFont。默认值为 True。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


在转换 Words 文档时替换特定字体。


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


如果 EmbedTrueTypeFonts 为 true，GroupDocs.Conversion 会在输出文档中嵌入 TrueType 字体。默认值：false


**Returns:**
布尔
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| embedTrueTypeFonts | 布尔 |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


加载后更新页面布局。默认值：false


**Returns:**
布尔
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updatePageLayout | 布尔 |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


加载后更新字段。默认值：false


**Returns:**
布尔
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updateFields | 布尔 |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


保留日期字段的原始值。默认值：false


**Returns:**
布尔
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


设置保留日期字段的原始值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keepDateFieldOriginalValue | 布尔 |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


在转换 Words 文档时替换特定字体。


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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


隐藏 Word 文档的标记和修订痕迹。


**Returns:**
布尔
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


隐藏 Word 文档的标记和修订痕迹。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


隐藏批注。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


书签选项


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


书签选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


指定是否在 PDF 中将 Microsoft Word 表单字段保留为表单字段，或将其转换为文本。默认值为 false。


**Returns:**
布尔型 - preserveFontFields 标志

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


设置 preserveFontFields 标志


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | preserveFontFields | 布尔 | 在 PDF 中保留 Microsoft Word 表单字段为表单字段或将其转换为文本 |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


指定是否使用文本整形器以获得更好的字距显示。默认值为 false。


**Returns:**
布尔
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


指定是否使用文本整形器以获得更好的字距显示。默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | isUseTextShaper | 布尔 | isUseTextShaper 标志 |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


确定在转换为 PDF 时是否应保留文档结构（默认值为 false）。请注意，导出文档结构会显著增加内存消耗，尤其是对于大型文档。


**Returns:**
布尔
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| preserveDocumentStructure | 布尔 |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


如果为 true，所有外部资源将不会加载，除非位于


**Returns:**
布尔
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| skip | 布尔 |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


始终会加载的外部资源


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


指定在输出文档中应如何显示注释。默认是 ShowInBalloons。


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


在注释中显示完整的评论者姓名。默认是 false。


**Returns:**
布尔
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| showFullCommenterName | 布尔 |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


启用或禁用在转换后文档中生成页码。默认： false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


获取 WordProcessing 文档的连字符选项。


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


设置 WordProcessing 文档的连字符选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


获取 InterruptThreadIfImageExceptionThrown 标志，默认值：false。如果为 true，则在图像处理线程出现异常时中断主转换线程。


**Returns:**
布尔
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


设置 InterruptThreadIfImageExceptionThrown 标志


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | 布尔 |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


启用后（默认），文本主要为从右到左（RTL）的段落和运行将在转换前修复其双向标志。


这与 Microsoft Word 和 LibreOffice 所采用的启发式方法相匹配，并且
修复由生成器生成的阿拉伯语/希伯来语文档的渲染问题
（尤其是 Google Docs）生成不含


以及含有

仅包含 RTL 脚本的运行时。


设置为
false
以保留对
源标记的严格 OOXML 解释。


**Returns:**
布尔
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


设置 autoDetectRtlDirection


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | autoDetectRtlDirection | 布尔 | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


获取选项以控制文档容器本身是否必须转换


**Returns:**
布尔
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwner | 布尔 |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


选项，用于控制文档容器中的所属文档是否必须转换


**Returns:**
布尔
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwned | 布尔 |  |

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

