---
title: WordProcessingLoadOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for loading WordProcessing documents.
type: docs
weight: 2830
url: /net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Options for loading WordProcessing documents.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IPageNumberingLoadOptions, 
    IResourceLoadingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initializes new instance of [`WordProcessingLoadOptions`](../wordprocessingloadoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Bookmarks options |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Removes built-in metadata properties from the document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Removes custom metadata properties from the document. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Specifies how comments should be displayed in the output document. Default is ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implements [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default is false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implements [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Default is true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Sets the default font for a WordProcessing document. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implements [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | If EmbedTrueTypeFonts is true, GroupDocs.Conversion embed true type fonts in the output document. Default: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Automatically substitutes missing fonts based on FontConfig in the system. Default: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Automatically substitutes missing fonts based on FontInfo in the document. Default: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Automatically substitutes missing fonts based on the font name. Default: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Substitutes specific fonts when converting a WordsProcessing document. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Input document file type. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Input document file type. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Hide markup and track changes for Word documents. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Set hyphenation options for WordProcessing documents. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Keep original value of date field. Default: false |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Enable or disable generation of page numbering in converted document. Default: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Set password to unprotect protected document. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Determines whether the document structure should be preserved when converting to PDF (default is false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Specifies whether to preserve Microsoft Word form fields as form fields in PDF or convert them to text. Default is false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Show full commenter name in comments. Default is false. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implements [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Update fields after loading. Default: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Update page layout after loading. Default: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Specifies whether to use a text shaper for better kerning display. Default is false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implements [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
