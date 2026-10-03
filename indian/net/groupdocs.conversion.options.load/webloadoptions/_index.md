---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "वेब दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 2920
url: /hi/net/groupdocs.conversion.options.load/webloadoptions/
---
## WebLoadOptions class

वेब दस्तावेज़ लोड करने के विकल्प।

```csharp
public class WebLoadOptions : LoadOptions, ICustomCssStyleOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageOrientationOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WebLoadOptions](webloadoptions)() | नया उदाहरण प्रारंभ करता है [`WebLoadOptions`](../webloadoptions) वर्ग का। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | HTML के लिए बेस पाथ/URL |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | रिक्वेस्ट हेडर्स की कॉन्फ़िगरेशन के लिए एक्शन। एक्शन का पहला पैरामीटर Uri है। |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Uri के लिए क्रेडेंशियल्स प्रोवाइडर। |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | इम्प्लीमेंट करता है [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | वेब दस्तावेज़ लोड करते समय उपयोग होने वाला एन्कोडिंग प्राप्त करता है या सेट करता है। यदि प्रॉपर्टी null है तो एन्कोडिंग दस्तावेज़ के कैरेक्टर सेट एट्रिब्यूट से निर्धारित की जाएगी। |
| [Format](../../groupdocs.conversion.options.load/webloadoptions/format) { get; set; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। यह `null` रहता है जब तक कोई फ़ॉर्मेट सेट नहीं किया जाता, इसलिए इसे `null` के लिए परीक्षण करें, न कि [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) के विरुद्ध, क्योंकि यह कभी बराबर नहीं होता। |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | HTML कंटेंट कैसे रेंडर किया जाता है, इसे नियंत्रित करता है। डिफ़ॉल्ट: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | पृष्ठ मार्जिन सेटिंग्स |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | पेज ओरिएंटेशन सेटिंग्स |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | वेब दस्तावेज़ लोड करते समय पेज लेआउट विकल्प निर्दिष्ट करता है। |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | परिवर्तित दस्तावेज़ में पृष्ठ क्रमांक जनरेशन को सक्षम या अक्षम करें। डिफ़ॉल्ट: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | बाहरी संसाधनों को लोड करने के लिए टाइमआउट |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | पृष्ठ आकार सेटिंग्स |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | लागू करता है [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | कन्वर्ज़न के लिए PDF का उपयोग करें। डिफ़ॉल्ट: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | लागू करता है [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | ज़ूम लेवल को प्रतिशत के रूप में निर्दिष्ट करता है। ज़ूम लेवल को कन्वर्ज़न से पहले दस्तावेज़ के &lt;body&gt; टैग पर लागू किया जाता है, जिससे दस्तावेज़ की दृश्य उपस्थिति स्केल होती है। 100% का मान मूल आकार को दर्शाता है। डिफ़ॉल्ट मान 100 है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### देखें भी

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
