---
title: EmailLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/emailloadoptions/
is_root: false
weight: 120
---

## EmailLoadOptions class

Options for loading Email documents.



**Inheritance:** [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The EmailLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/__init__/#) | Initializes new instance of [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/format) | Input document file type. |
| [display_header](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_header) | Option to display or hide the email header. Default: true. |
| [display_from_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_from_email_address) | Option to display or hide "from" email address. Default: true. |
| [display_to_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_to_email_address) | Option to display or hide "to" email address. Default: true. |
| [display_cc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_cc_email_address) | Option to display or hide "Cc" email address. Default: false. |
| [display_bcc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_bcc_email_address) | Option to display or hide "Bcc" email address. Default: false. |
| [display_attachments](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_attachments) | Option to display or hide attachments in the header. Default: true. |
| [display_subject](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_subject) | Option to display or hide subject in the header. Default: true. |
| [display_sent](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_sent) | Option to display or hide sent date/time in the header. Default: true. |
| [time_zone_offset](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/time_zone_offset) | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the localtime and UTC. |
| [field_text_map](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/field_text_map) | The mapping between email message [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield) and field text representation |
| [preserve_original_date](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/preserve_original_date) | Defines whether need to keep original date header string in mail message when saving or not (Default value is true) |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owner) | Implements [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owner)<br/><br/>Default is true |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owned) | Implements [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owned)<br/><br/>Default is true |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/depth) | Implements [`IDocumentsContainerLoadOptions.depth`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#depth)<br/><br/>Default: 1 |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/resource_loading_timeout) | Timeout for loading external resources |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/clone/#) | Clones current instance. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield)
* class [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
