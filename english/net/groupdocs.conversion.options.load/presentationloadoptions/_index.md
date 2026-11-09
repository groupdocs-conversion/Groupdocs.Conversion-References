---
title: PresentationLoadOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for loading Presentation documents.
type: docs
weight: 2800
url: /net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Options for loading Presentation documents.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IPasswordLoadOptions, IResourceLoadingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | Initializes new instance of [`PresentationLoadOptions`](../presentationloadoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | Removes built-in metadata properties from the document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | Removes custom metadata properties from the document. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | Represents the way comments are printed with the slide. Default is None. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | Implements [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default is false |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | Implements [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Default is true |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | Default font for rendering the presentation. The following font will be used if a presentation font is missing. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | Implements [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) How many levels of contained documents the conversion goes down, counted from the document the conversion starts from, which is level 0: 0 or a negative value converts no contained document, 1 converts the documents it contains directly, 2 also the documents those contain, and so on. On the document the conversion starts from, it is the limit for the whole conversion. Returned by the load options callback for a contained document at level L, it limits the documents that document contains to level L + Depth, never deeper than the limit of the document the conversion starts from. Default: 2 |
| [ExternalResourceHandler](../../groupdocs.conversion.options.load/presentationloadoptions/externalresourcehandler) { get; set; } | Gets or sets the handler called for each resource the document asks an engine to load. Default: `null`. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | Substitute specific fonts when converting Presentation document. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | Input document file type. Is `null` until a format has been set, so test it for `null` rather than against [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), which it never equals. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Input document file type. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | Represents the way notes are printed with the slide. Default is None. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | Set password to unprotect protected document. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | Determines whether the document structure should be preserved when converting to PDF (default is false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | Show hidden slides. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | Gets or sets whether external resources are denied. Default: `true`. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | Gets or sets the absolute URI prefixes of the external resources that load while [`SkipExternalResources`](./skipexternalresources) is `true`. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | Set video document connector |

### See Also

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPasswordLoadOptions](../ipasswordloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
