---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "WordProcessing दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 2950
url: /hi/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

WordProcessing दस्तावेज़ लोड करने के विकल्प।

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | [`WordProcessingLoadOptions`](../wordprocessingloadoptions) क्लास का नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | जब true (डिफ़ॉल्ट) हो, तो पैराग्राफ़ और रन जिनका टेक्स्ट मुख्यतः दाएँ‑से‑बाएँ होता है, उनके बिडी फ़्लैग्स को रूपांतरण से पहले ठीक किया जाएगा। यह माइक्रोसॉफ्ट वर्ड और लिब्रेऑफ़िस द्वारा लागू किए गए heuristic से मेल खाता है और उन जेनरेटरों (विशेष रूप से गूगल डॉक्स) द्वारा उत्पन्न अरबी/हिब्रू दस्तावेज़ों की रेंडरिंग को ठीक करता है, जो OOXML को बिना &lt;w:bidi/&gt; के और केवल RTL स्क्रिप्ट वाले रन पर &lt;w:rtl w:val="0"/&gt; के साथ उत्पन्न करते हैं। false सेट करने पर स्रोत मार्कअप की सख़्त OOXML व्याख्या को संरक्षित रखा जाता है। |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | बुकमार्क विकल्प |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | दस्तावेज़ से अंतर्निहित मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | दस्तावेज़ से कस्टम मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | निर्दिष्ट करता है कि आउटपुट दस्तावेज़ में टिप्पणियों को कैसे प्रदर्शित किया जाना चाहिए। डिफ़ॉल्ट ShowInBalloons है। |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | लागू करता है [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) डिफ़ॉल्ट false है |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | लागू करता है [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) डिफ़ॉल्ट true है |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | WordProcessing दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट सेट करता है। |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | लागू करता है [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) डिफ़ॉल्ट: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | यदि EmbedTrueTypeFonts true है, तो GroupDocs.Conversion आउटपुट दस्तावेज़ में true type फ़ॉन्ट एम्बेड करता है। डिफ़ॉल्ट: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | सिस्टम में FontConfig के आधार पर गायब फ़ॉन्ट्स को स्वचालित रूप से बदलता है। डिफ़ॉल्ट: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | दस्तावेज़ में FontInfo के आधार पर गायब फ़ॉन्ट्स को स्वचालित रूप से बदलता है। डिफ़ॉल्ट: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | फ़ॉन्ट नाम के आधार पर गायब फ़ॉन्ट्स को स्वचालित रूप से बदलता है। डिफ़ॉल्ट: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | WordsProcessing दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट्स को बदलता है। |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | दस्तावेज़ लोड होने और फ़ॉन्ट प्रतिस्थापन पूर्ण होने के बाद मौजूदा फ़ॉन्ट्स को बदलें। फ़ॉन्ट परिवर्तन दस्तावेज़ में किसी भी फ़ॉन्ट को संशोधित कर सकते हैं, जिसमें सफलतापूर्वक लोड किए गए फ़ॉन्ट्स भी शामिल हैं। |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। यह `null` रहता है जब तक कोई फ़ॉर्मेट सेट नहीं किया जाता, इसलिए इसे `null` के लिए परीक्षण करें, न कि [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) के विरुद्ध, क्योंकि यह कभी बराबर नहीं होता। |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Word दस्तावेज़ों के लिए मार्कअप और ट्रैक परिवर्तन को छिपाएँ। |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | WordProcessing दस्तावेज़ों के लिए हाइफ़नेशन विकल्प सेट करें। |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | तारीख फ़ील्ड का मूल मान रखें। डिफ़ॉल्ट: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | पृष्ठ मार्जिन सेटिंग्स |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | परिवर्तित दस्तावेज़ में पृष्ठ क्रमांक जनरेशन को सक्षम या अक्षम करें। डिफ़ॉल्ट: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | निर्धारित करता है कि PDF में परिवर्तित करते समय दस्तावेज़ संरचना को संरक्षित किया जाना चाहिए या नहीं (डिफ़ॉल्ट false है)। |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | निर्दिष्ट करता है कि Microsoft Word फ़ॉर्म फ़ील्ड्स को PDF में फ़ॉर्म फ़ील्ड्स के रूप में संरक्षित किया जाए या उन्हें टेक्स्ट में परिवर्तित किया जाए। डिफ़ॉल्ट false है। |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | टिप्पणियों में पूर्ण टिप्पणीकर्ता नाम दिखाएँ। डिफ़ॉल्ट false है। |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | पृष्ठ आकार सेटिंग्स |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | लागू करता है [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | लोड होने के बाद फ़ील्ड्स को अपडेट करें। डिफ़ॉल्ट: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | लोड होने के बाद पृष्ठ लेआउट को अपडेट करें। डिफ़ॉल्ट: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | बेहतर केरनिंग डिस्प्ले के लिए टेक्स्ट शेपर का उपयोग करना है या नहीं, निर्दिष्ट करता है। डिफ़ॉल्ट false है। |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | लागू करता है [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### टिप्पणियाँ

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• फ़ॉन्ट सब्स्टिट्यूट्स, डिफ़ॉल्टफ़ॉन्ट और सिस्टम प्रतिस्थापन का उपयोग करके अनुपलब्ध/गायब फ़ॉन्ट्स को संभालता है

• प्रोसेसिंग क्रम: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• FontReplacements का उपयोग करके लोडेड दस्तावेज़ में मौजूद किसी भी फ़ॉन्ट को संशोधित करता है

• सभी फ़ॉन्ट प्रतिस्थापन पूर्ण होने के बाद लागू किया जाता है

### देखें भी

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
