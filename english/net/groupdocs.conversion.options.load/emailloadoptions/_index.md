---
title: EmailLoadOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for loading Email documents.
type: docs
weight: 2230
url: /net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Options for loading Email documents.

```csharp
public sealed class EmailLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Initializes new instance of [`EmailLoadOptions`](../emailloadoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implements [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default is true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Implements [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Default is true |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Default font for email document. The following font will be used if a font is missing. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Implements [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Option to display or hide attachments in the header. Default: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Option to display or hide "Bcc" email address. Default: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Option to display or hide "Cc" email address. Default: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Option to control whether email addresses are displayed alongside names. Example: "John Doe &lt;john.doe@sample.com&gt;" or just "John Doe." Default: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Option to display or hide "from" email address. Default: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Option to display or hide the email header. Default: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Option to display or hide sent date/time in the header. Default: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Option to display or hide subject in the header. Default: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Option to display or hide "to" email address. Default: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | The mapping between email message [`EmailField`](../emailfield) and field text representation |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | List of font substitutes. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Input document file type. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Input document file type. |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Defines whether need to keep original date header string in mail message when saving or not (Default value is true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Timeout for loading external resources |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the localtime and UTC. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Clones current instance. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
