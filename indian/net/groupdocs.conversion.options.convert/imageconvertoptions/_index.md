---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "इमेज फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 1950
url: /hi/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

इमेज फ़ाइल प्रकार में रूपांतरण के विकल्प।

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | नया उदाहरण प्रारंभ करता है [`ImageConvertOptions`](../imageconvertoptions) क्लास का। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | स्रोत फ़ॉर्मेट द्वारा समर्थित होने पर पृष्ठभूमि रंग सेट करता है। |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | छवि की चमक समायोजित करता है। |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | जब सेट किया जाता है, तो प्रति‑पृष्ठ PDF रेंडर रिज़ॉल्यूशन को पृष्ठ के मूल रास्टर रिज़ॉल्यूशन तक सीमित कर देता है ताकि कोई पृष्ठ उसकी एम्बेडेड छवि की वास्तविक DPI से अधिक DPI पर रेंडर न हो, और अंतिम आउटपुट में उस पृष्ठ को उसके मूल (छोटे) पिक्सेल आयाम और मूल DPI पर जारी करता है, न कि अनुरोधित DPI पर पुनः बढ़ाया जाए। केवल छवि‑प्रधान (स्कैन) पृष्ठ प्रभावित होते हैं; टेक्स्ट या वेक्टर सामग्री वाले पृष्ठ कभी सॉफ़्ट नहीं होते और अनुरोधित DPI पर जारी किए जाते हैं। जब स्पष्ट आउटपुट [`Width`](./width) या [`Height`](./height) सेट किया जाता है तो यह चरण छोड़ दिया जाता है। डिफ़ॉल्ट `false` है (कोई सीमांकन नहीं; प्रत्येक पृष्ठ अनुरोधित DPI पर रेंडर और जारी किया जाता है)। |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | छवि का कंट्रास्ट समायोजित करता है। |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | रूपांतरण के बाद रास्टर छवि क्षेत्र को क्रॉप करें। |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | छवि फ़्लिप मोड। |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | इनपुट दस्तावेज़ को जिस वांछित फ़ाइल प्रकार में परिवर्तित किया जाना चाहिए। |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | लागू करता है [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | छवि गामा समायोजित करता है। |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | निर्देशित करता है कि ग्रेस्केल छवि में परिवर्तित करना है या नहीं। |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | रूपांतरण के बाद वांछित छवि ऊँचाई। |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | रूपांतरण के बाद वांछित छवि क्षैतिज रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल का रिज़ॉल्यूशन या 96 dpi है। |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg विशिष्ट रूपांतरण विकल्प। |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | जब [`CapResolutionToPageContent`](./capresolutiontopagecontent) सक्षम हो, तो सीमित रेंडर DPI पर प्रति‑अक्ष निचली सीमा लागू की जाती है। सीमित DPI कभी इस मान से नीचे नहीं जाती। डिफ़ॉल्ट `0` है (कोई फ़्लोर नहीं)। |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | लागू करता है [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | लागू करता है [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | लागू करता है [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd विशिष्ट रूपांतरण विकल्प। |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | छवि घुमाव कोण। |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff विशेष रूपांतरण विकल्प। |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | यदि `true` है, तो इनपुट पहले PDF में परिवर्तित होता है और फिर इच्छित फ़ॉर्मेट में। |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | रूपांतरण के बाद वांछित छवि की लंबवत रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi है। |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | लागू करता है [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp विशेष रूपांतरण विकल्प। |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | रूपांतरण के बाद वांछित छवि की चौड़ाई। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | वर्तमान विकल्पों के उदाहरण को क्लोन करता है। |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### देखें भी

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
