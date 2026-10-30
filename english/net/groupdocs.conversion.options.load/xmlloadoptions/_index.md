---
title: XmlLoadOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for loading XML documents.
type: docs
weight: 2980
url: /net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Options for loading XML documents.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Initializes new instance of [`XmlLoadOptions`](../xmlloadoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | The base directory or URL that relative references in the document resolve against. |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Action for configuration of the request headers. First parameter of the action is the Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Credentials provider for the Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Implements [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Get or sets the encoding to be used when loading the web document. If the property is null the encoding will be determined from document character set attribute |
| [ExecuteScripts](../../groupdocs.conversion.options.load/webloadoptions/executescripts) { get; set; } | Gets or sets whether the document's scripts run while it loads and converts. Default: `false`. |
| [ExternalResourceHandler](../../groupdocs.conversion.options.load/webloadoptions/externalresourcehandler) { get; set; } | Gets or sets the handler called for each resource the document asks an engine to load. Default: `null`. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Input document file type. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Input document file type. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Controls how HTML content is rendered. Default: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Page margin settings |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Page orientation settings |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Specifies the page layout options when loading web documents. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Enable or disable generation of page numbering in converted document. Default: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Timeout for loading external resources |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Page size settings |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Gets or sets whether external resources are denied. Default: `true`. |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Use Xml document as data source |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Use pdf for the conversion. Default: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Gets or sets the absolute URI prefixes of the external resources that load while [`SkipExternalResources`](../webloadoptions/skipexternalresources) is `true`. |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | XSL-FO document stream to convert XML using XSL-FO markup file. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | XSLT document stream to convert XML performing XSL transformation to HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Specifies the zoom level as a percentage. The zoom level is applied to the document's &lt;body&gt; tag before conversion, scaling the document's visual appearance. A value of 100% represents the original size. The default value is 100. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
