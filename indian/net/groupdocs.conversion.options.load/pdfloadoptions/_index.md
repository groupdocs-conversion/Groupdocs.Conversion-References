---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "Pdf दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 2740
url: /hi/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Pdf दस्तावेज़ लोड करने के विकल्प।

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | [`PdfLoadOptions`](../pdfloadoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | दस्तावेज़ से अंतर्निहित मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | दस्तावेज़ से कस्टम मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | लागू करता है [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) डिफ़ॉल्ट false है |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | लागू करता है [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) डिफ़ॉल्ट true है |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Pdf दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट गायब है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा। |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | लागू करता है [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) डिफ़ॉल्ट: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | PDF फ़ॉर्म के सभी फ़ील्ड को फ्लैटेन करें। |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Pdf दस्तावेज़ को रूपांतरित करते समय विशिष्ट फ़ॉन्ट को बदलें। |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | दस्तावेज़ लोड होने और फ़ॉन्ट प्रतिस्थापन पूर्ण होने के बाद मौजूदा फ़ॉन्ट्स को बदलें। फ़ॉन्ट परिवर्तन दस्तावेज़ में किसी भी फ़ॉन्ट को संशोधित कर सकते हैं, जिसमें सफलतापूर्वक लोड किए गए फ़ॉन्ट्स भी शामिल हैं। |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। यह `null` रहता है जब तक कोई फ़ॉर्मेट सेट नहीं किया जाता, इसलिए इसे `null` के लिए परीक्षण करें, न कि [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) के विरुद्ध, क्योंकि यह कभी बराबर नहीं होता। |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Pdf दस्तावेज़ों में एनोटेशन छिपाएँ। |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | परिवर्तित दस्तावेज़ में पृष्ठ क्रमांक जनरेशन को सक्षम या अक्षम करें। डिफ़ॉल्ट: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | एम्बेडेड फ़ाइलें हटाएँ। |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | जावास्क्रिप्ट हटाएँ। |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### देखें भी

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
