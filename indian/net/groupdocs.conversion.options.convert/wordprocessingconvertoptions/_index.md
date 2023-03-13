---
title: WordProcessingConvertOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: वर्डप्रसेसंग फ़इल प्रकर में रूपंतरण के लए वकल्प
type: docs
weight: 2000
url: /hi/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

वर्डप्रोसेसिंग फ़ाइल प्रकार में रूपांतरण के लिए विकल्प।

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | का नया उदाहरण शुरू करता है[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | वांछित पृष्ठ डीपीआई रूपांतरण के बाद। डिफ़ॉल्ट रिज़ॉल्यूशन है: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | वांछित फ़ाइल प्रकार इनपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | वांछित फ़ाइल प्रकार इनपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | रूपांतरण के बाद वांछित पृष्ठ ऊंचाई। |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | रूपांतरण के बाद पिक्सेल में वांछित पृष्ठ निचला मार्जिन। |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | रूपांतरण के बाद पिक्सेल में वांछित पृष्ठ का बायाँ हाशिया। |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | रूपांतरण के बाद पिक्सेल में वांछित पृष्ठ दायां मार्जिन। |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | रूपांतरण के बाद पिक्सेल में वांछित पृष्ठ शीर्ष मार्जिन। |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | रूपांतरण शुरू करने के लिए पृष्ठ संख्या. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | परिवर्तन के बाद वांछित पेज ओरिएंटेशन |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | कनवर्ट किए जाने वाले पेज इंडेक्स की सूची। विशिष्ट पृष्ठों को परिवर्तित करने के लिए निर्दिष्ट किया जाना चाहिए। |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | से शुरू करने के लिए पृष्ठों की संख्या`पृष्ठ संख्या` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | रूपांतरण के बाद वांछित पृष्ठ आकार |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस संपत्ति को सेट करें। |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | pdf से कनवर्ट करते समय पहचान मोड |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | आरटीएफ विशिष्ट कन्वर्ट विकल्प |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | वॉटरमार्क विशिष्ट विकल्प |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | रूपांतरण के बाद वांछित पृष्ठ चौड़ाई। |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है। Microsoft Word 2010 तक डिफ़ॉल्ट ज़ूम समर्थित है। Microsoft Word 2013 से शुरू होकर डिफ़ॉल्ट ज़ूम अब दस्तावेज़ पर सेट नहीं है, इसके बजाय यह पिछले दस्तावेज़ के ज़ूम कारक का उपयोग करता है जो खोला गया था। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | क्लोन वर्तमान विकल्प उदाहरण। |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### यह सभी देखें

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* नाम स्थान [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
