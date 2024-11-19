---
title: PresentationLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 380
url: /python-net/groupdocs.conversion.options.load/presentationloadoptions/
is_root: false
---

## PresentationLoadOptions class

Options for loading Presentation documents.



**Inheritance:** [`PresentationLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The PresentationLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/__init__/#) | Initializes new instance of [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/format) | Input document file type. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/default_font) | Default font for rendering the presentation. The following font will be used if a presentation font is missing. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/font_substitutes) | Substitute specific fonts when converting Presentation document. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/password) | Set password to unprotect protected document. |
| [hide_comments](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/hide_comments) | Hide comments. |
| [show_hidden_slides](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/show_hidden_slides) | Show hidden slides. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/skip_external_resources) | Implements [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#skip_external_resources) |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/whitelisted_resources) | Implements [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#whitelisted_resources) |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/convert_owner) | Implements [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owner)<br/><br/>Default is true |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/convert_owned) | Implements [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owned)<br/><br/>Default is false |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/depth) | Implements [`IDocumentsContainerLoadOptions.depth`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#depth)<br/><br/>Default: 1 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/clear_built_in_document_properties) | Removes built-in metadata properties from the document. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/clear_custom_document_properties) | Removes custom metadata properties from the document. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`PresentationLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/presentationloadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
