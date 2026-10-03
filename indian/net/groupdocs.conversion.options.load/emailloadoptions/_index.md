---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "ईमेल दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 2500
url: /hi/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

ईमेल दस्तावेज़ लोड करने के विकल्प।

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | नया उदाहरण प्रारंभ करता है [`EmailLoadOptions`](../emailloadoptions) वर्ग का। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | अटैचमेंट आइकनों की सूची प्राप्त करता या सेट करता है। सूची को विभिन्न फ़ाइल प्रकारों के लिए विशिष्ट आइकन प्रदान करने हेतु अनुकूलित किया जा सकता है। डिफ़ॉल्ट रूप से, इसमें सामान्य फ़ाइल प्रकार के आइकन शामिल हैं। |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implements [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default is true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | लागू करता है [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) डिफ़ॉल्ट true है |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | इम्प्लीमेंट करता है [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | ईमेल दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा। |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | लागू करता है [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) डिफ़ॉल्ट: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | हेडर में अटैचमेंट दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | \"Bcc\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | \"Cc\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | ईमेल पते को नामों के साथ दिखाया जाए या नहीं, इसे नियंत्रित करने का विकल्प। उदाहरण: \"John Doe &lt;john.doe@sample.com&gt;\" या केवल \"John Doe.\" डिफ़ॉल्ट: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | \"from\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | ईमेल हेडर दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | हेडर में भेजे गए तिथि/समय को दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | हेडर में विषय दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | \"to\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | ईमेल संदेश और फ़ील्ड टेक्स्ट प्रतिनिधित्व के बीच का मैपिंग [`EmailField`](../emailfield) |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | फ़ॉन्ट विकल्पों की सूची। |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। यह `null` रहता है जब तक कोई फ़ॉर्मेट सेट नहीं किया जाता, इसलिए इसे `null` के लिए परीक्षण करें, न कि [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) के विरुद्ध, क्योंकि यह कभी बराबर नहीं होता। |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | पृष्ठ मार्जिन सेटिंग्स |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | पेज ओरिएंटेशन सेटिंग्स |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | को लागू करता है [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | सेव करते समय मेल संदेश में मूल तिथि हेडर स्ट्रिंग को रखना आवश्यक है या नहीं, इसे परिभाषित करता है (डिफ़ॉल्ट मान true है)। |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | बाहरी संसाधनों को लोड करने के लिए टाइमआउट |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | पृष्ठ आकार सेटिंग्स |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | लागू करता है [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | संदेश तिथियों के लिए कोऑर्डिनेटेड यूनिवर्सल टाइम (UTC) ऑफ़सेट प्राप्त करता है या सेट करता है। यह प्रॉपर्टी स्थानीय समय और UTC के बीच समय क्षेत्र अंतर को परिभाषित करती है। |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | डिफ़ॉल्ट अटैचमेंट आइकन उपयोग करने के लिए प्राप्त करता है या सेट करता है। डिफ़ॉल्ट: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | लागू करता है [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | वर्तमान इंस्टेंस को क्लोन करता है। |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### देखें भी

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
