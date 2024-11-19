---
title: WebLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 510
url: /python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
---

## WebLoadOptions class

Options for loading web documents.



**Inheritance:** [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The WebLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/#) | Initializes new instance of [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format) | Input document file type. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering) | Enable or disable generation of page numbering in converted document. Default: false |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path) | The base path/url for the html |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding) | Get or sets the encoding to be used when loading the web document.<br/>If the property is null the encoding will be determined from document character set attribute |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout) | Timeout for loading external resources |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources) | Implements [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#skip_external_resources) |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources) | Implements [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#whitelisted_resources) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf) | Use pdf for the conversion. Default: false |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers) | Interface for configuring request headers. The implementation should define the behavior for configuring headers based on the URI. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider) | Credentials provider for the URI. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
* class [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions)
