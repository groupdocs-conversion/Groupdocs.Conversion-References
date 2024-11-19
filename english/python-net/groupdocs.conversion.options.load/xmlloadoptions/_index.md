---
title: XmlLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 540
url: /python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
---

## XmlLoadOptions class

Options for loading XML documents.



**Inheritance:** [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions) → 
[`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The XmlLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/#) | Initializes new instance of [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format) | Input document file type. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering) | Enable or disable generation of page numbering in converted document. Default: false |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/base_path) | The base path/url for the html |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/encoding) | Get or sets the encoding to be used when loading the web document.<br/>If the property is null the encoding will be determined from document character set attribute |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/resource_loading_timeout) | Timeout for loading external resources |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources) | Implements [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#skip_external_resources) |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources) | Implements [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions#whitelisted_resources) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_pdf) | Use pdf for the conversion. Default: false |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/configure_headers) | Interface for configuring request headers. The implementation should define the behavior for configuring headers based on the URI. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/credentials_provider) | Credentials provider for the URI. |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory) | XSL-FO document stream to convert XML using XSL-FO markup file. |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory) | XSLT document stream to convert XML performing XSL transformation to HTML. |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source) | Use Xml document as data source |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
* class [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions)
* class [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions)
