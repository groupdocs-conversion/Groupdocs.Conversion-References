---
title: WordProcessingLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 530
url: /python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
---

## WordProcessingLoadOptions class

Options for loading WordProcessing documents.



**Inheritance:** [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The WordProcessingLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/#) | Initializes new instance of [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format) | Input document file type. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font) | Default font for Words document. The following font will be used if a font is missing. |
| [auto_font_substitution](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_font_substitution) | If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. If AutoFontSubstitution is enabled,<br/>GroupDocs.Conversion evaluates all the related fields in FontInfo (Panose, Sig etc) for the missing font and finds the closest match among the available font sources.<br/>Note that font substitution mechanism will override the DefaultFont in cases when FontInfo for the missing font is available in the document. The default value is True. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts) | If EmbedTrueTypeFonts is true, GroupDocs.Conversion embed true type fonts in the output document. Default: false |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout) | Update page layout after loading. Default: false |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields) | Update fields after loading. Default: false |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value) | Keep original value of date field. Default: false |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes) | Substitute specific fonts when converting Words document. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password) | Set password to unprotect protected document. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes) | Hide markup and track changes for Word documents. |
| [hide_comments](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_comments) | Hide comments. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options) | Bookmarks options |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields) | Specifies whether to preserve Microsoft Word form fields as form fields in PDF or convert them to text. Default is false. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper) | Specifies whether to use a text shaper for better kerning display. Default is false. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources) | Implements [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#skip_external_resources) |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources) | Implements [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#whitelisted_resources) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure) | Determines whether the document structure should be preserved when converting to PDF (default is false). |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering) | Enable or disable generation of page numbering in converted document. Default: false |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options) | Set hyphenation options for WordProcessing documents. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner) | Implements [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owner)<br/><br/>Default is true |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned) | Implements [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owned)<br/><br/>Default is false |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth) | Implements [`IDocumentsContainerLoadOptions.depth`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#depth)<br/><br/>Default: 1 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties) | Removes built-in metadata properties from the document. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties) | Removes custom metadata properties from the document. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions)
