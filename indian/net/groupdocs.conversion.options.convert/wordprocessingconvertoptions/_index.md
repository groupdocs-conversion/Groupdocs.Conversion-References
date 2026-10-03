---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "वर्ड प्रोसेसिंग फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 2340
url: /hi/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

वर्ड प्रोसेसिंग फ़ाइल प्रकार में रूपांतरण के विकल्प।

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, 
    IPasswordConvertOptions, IPdfRecognitionModeOptions, IZoomConvertOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | नया उदाहरण प्रारंभ करता है [`WordProcessingConvertOptions`](../wordprocessingconvertoptions) क्लास का। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | परिवर्तन के बाद वांछित पृष्ठ DPI। डिफ़ॉल्ट रिज़ॉल्यूशन है: 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | फ़ॉलबैक पृष्ठ आकार |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | इनपुट दस्तावेज़ को जिस वांछित फ़ाइल प्रकार में परिवर्तित किया जाना चाहिए। |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | लागू करता है [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginsettings) { get; set; } | पृष्ठ मार्जिन सेटिंग्स |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | इम्प्लीमेंट करता है [`MarkdownOptions`](./markdownoptions) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientationsettings) { get; set; } | पेज ओरिएंटेशन सेटिंग्स |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | लागू करता है [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | लागू करता है [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | लागू करता है [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस गुण को सेट करें। |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | इम्प्लीमेंट करता है [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | RTF विशिष्ट रूपांतरण विकल्प |
| [SizeSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/sizesettings) { get; set; } | पृष्ठ आकार सेटिंग्स |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | लागू करता है [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है। डिफ़ॉल्ट ज़ूम Microsoft Word 2010 तक समर्थित है। Microsoft Word 2013 से डिफ़ॉल्ट ज़ूम अब दस्तावेज़ पर सेट नहीं किया जाता, बल्कि यह खुली अंतिम दस्तावेज़ के ज़ूम फैक्टर का उपयोग करता प्रतीत होता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | वर्तमान विकल्पों के उदाहरण को क्लोन करता है। |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### देखें भी

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
