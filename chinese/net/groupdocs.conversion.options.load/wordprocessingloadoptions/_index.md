---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 WordProcessing 文档的选项。"
type: docs
weight: 2950
url: /zh/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

加载 WordProcessing 文档的选项。

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | 初始化 [`WordProcessingLoadOptions`](../wordprocessingloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | 当为 true（默认）时，文本主要为从右到左的段落和运行将在转换前修复其 bidi 标志。这与 Microsoft Word 和 LibreOffice 使用的启发式方法相匹配，并修复了由生成器（尤其是 Google Docs）生成的阿拉伯语/希伯来语文档的渲染问题，这些文档在仅包含 RTL 脚本的运行中未包含 &lt;w:bidi/&gt; 且使用 &lt;w:rtl w:val="0"/&gt;。将其设为 false 可保留对源标记的严格 OOXML 解释。 |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | 书签选项 |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | 从文档中移除内置的元数据属性。 |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | 从文档中移除自定义元数据属性。 |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | 指定在输出文档中如何显示批注。默认是 ShowInBalloons。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | 实现 [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) 默认值为 false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | 实现 [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) 默认值为 true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | 设置 WordProcessing 文档的默认字体。 |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | 实现 [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) 默认值：1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | 如果 EmbedTrueTypeFonts 为 true，GroupDocs.Conversion 会在输出文档中嵌入 TrueType 字体。默认值：true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | 基于系统中的 FontConfig 自动替换缺失的字体。默认值：false。 |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | 基于文档中的 FontInfo 自动替换缺失的字体。默认值：false。 |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | 基于字体名称自动替换缺失的字体。默认值：false。 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | 在转换 WordsProcessing 文档时替换特定字体。 |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | 在文档加载和字体替换完成后转换现有字体。字体转换可以修改文档中的任何字体，包括已成功加载的字体。 |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | 隐藏 Word 文档的标记和修订痕迹。 |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | 设置 WordProcessing 文档的连字符选项。 |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | 保留日期字段的原始值。默认值：false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | 页面边距设置 |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | 启用或禁用在转换后文档中生成页码。默认值：false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | 设置密码以解除受保护文档的保护。 |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | 确定在转换为 PDF 时是否应保留文档结构（默认值为 false）。 |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | 指定是将 Microsoft Word 表单字段在 PDF 中保留为表单字段，还是将其转换为文本。默认值为 false。 |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | 在批注中显示完整的评论者姓名。默认值为 false。 |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | 页面尺寸设置 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | 实现 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | 加载后更新字段。默认值：false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | 加载后更新页面布局。默认值：false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | 指定是否使用文本整形器以获得更好的字距显示。默认值为 false。 |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | 实现 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 备注

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• 使用 FontSubstitutes、DefaultFont 和系统替代处理缺失/不可用的字体

• 处理顺序：FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• 使用 FontReplacements 修改加载文档中已有的字体

• 在所有字体替换完成后应用

### 另见

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
