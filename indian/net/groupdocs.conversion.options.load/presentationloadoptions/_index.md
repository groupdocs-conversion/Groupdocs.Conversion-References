---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "Presentation दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 2770
url: /hi/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Presentation दस्तावेज़ लोड करने के विकल्प।

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | [`PresentationLoadOptions`](../presentationloadoptions) क्लास का नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | दस्तावेज़ से अंतर्निहित मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | दस्तावेज़ से कस्टम मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | स्लाइड के साथ टिप्पणियों के प्रिंट होने के तरीके को दर्शाता है। डिफ़ॉल्ट मान None है। |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | लागू करता है [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) डिफ़ॉल्ट false है |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | लागू करता है [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) डिफ़ॉल्ट true है |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | प्रेजेंटेशन रेंडर करने के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि प्रेजेंटेशन फ़ॉन्ट अनुपलब्ध है तो नीचे दिया गया फ़ॉन्ट उपयोग किया जाएगा। |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | लागू करता है [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) डिफ़ॉल्ट: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | प्रेजेंटेशन दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट्स को बदलें। |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। यह `null` रहता है जब तक कोई फ़ॉर्मेट सेट नहीं किया जाता, इसलिए इसे `null` के लिए परीक्षण करें, न कि [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) के विरुद्ध, क्योंकि यह कभी बराबर नहीं होता। |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | स्लाइड के साथ नोट्स के प्रिंट होने के तरीके को दर्शाता है। डिफ़ॉल्ट मान None है। |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | निर्धारित करता है कि PDF में परिवर्तित करते समय दस्तावेज़ संरचना को संरक्षित किया जाना चाहिए या नहीं (डिफ़ॉल्ट false है)। |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | छिपी हुई स्लाइड्स दिखाएँ। |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | लागू करता है [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | लागू करता है [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | वीडियो डॉक्यूमेंट कनेक्टर सेट करें |

### देखें भी

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
