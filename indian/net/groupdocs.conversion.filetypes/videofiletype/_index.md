---
title: "VideoFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "वीडियो दस्तावेज़ों को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं Mp4./videofiletype/mp4 Avi./videofiletype/avi Flv./videofiletype/flv Mkv./videofiletype/mkv Mov./videofiletype/mov Webm./videofiletype/webm Wmv./videofiletype/wmv वीडियो फ़ॉर्मेट के बारे में अधिक जानें herehttps//docs.fileformat.com/video/."
type: docs
weight: 1260
url: /hi/net/groupdocs.conversion.filetypes/videofiletype/
---
## VideoFileType class

वीडियो दस्तावेज़ों को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं: [`Mp4`](./mp4), [`Avi`](./avi), [`Flv`](./flv), [`Mkv`](./mkv), [`Mov`](./mov), [`Webm`](./webm), [`Wmv`](./wmv), वीडियो फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/video/).

```csharp
public sealed class VideoFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VideoFileType](videofiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | फ़ाइल प्रकार विवरण |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | फ़ाइल एक्सटेंशन |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | फ़ाइल परिवार |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल फ़ॉर्मेट |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | वर्तमान ऑब्जेक्ट की तुलना अन्य से करता है। |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) को लागू करता है। |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | स्ट्रिंग प्रतिनिधित्व |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [Avi](../../groupdocs.conversion.filetypes/videofiletype/avi) | AVI फ़ाइल फ़ॉर्मेट एक ऑडियो वीडियो मल्टीमीडिया कंटेनर फ़ाइल फ़ॉर्मेट है जिसे माइक्रोसॉफ्ट ने प्रस्तुत किया था। यह ऑडियो और वीडियो डेटा को कई कोडेक (कोडर/डिकोडर) जैसे XVid और DivX का उपयोग करके बनाया और संकुचित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](https://docs.fileformat.com/video/avi/). |
| static readonly [Flv](../../groupdocs.conversion.filetypes/videofiletype/flv) | FLV (Flash Video) एक कंटेनर फ़ाइल फ़ॉर्मेट है जिसमें .flv एक्सटेंशन होता है। FLV का उपयोग इंटरनेट पर ऑडियो/वीडियो सामग्री को Adobe Flash Player या Adobe Air के माध्यम से डिलीवर करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/video/flv/) देखें। |
| static readonly [Mkv](../../groupdocs.conversion.filetypes/videofiletype/mkv) | MKV (Matroska Video) एक मल्टीमीडिया कंटेनर है जो MOV और AVI फ़ॉर्मेट के समान है लेकिन यह एक ही फ़ाइल में एक से अधिक ऑडियो और सबटाइटल ट्रैक का समर्थन करता है। MKV फ़ाइल Matroska मल्टीमीडिया कंटेनर फ़ॉर्मेट है जो वीडियो के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/video/mkv/) देखें। |
| static readonly [Mov](../../groupdocs.conversion.filetypes/videofiletype/mov) | MOV या QuickTime फ़ाइल फ़ॉर्मेट एक मल्टीमीडिया कंटेनर है जिसे Apple ने विकसित किया है: इसमें एक या अधिक ट्रैक होते हैं, प्रत्येक ट्रैक विशेष प्रकार का डेटा रखता है जैसे वीडियो, ऑडियो, टेक्स्ट आदि। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/video/mov/) देखें। |
| static readonly [Mp4](../../groupdocs.conversion.filetypes/videofiletype/mp4) | MP4 (MPEG-4 Part 14 का संक्षिप्त रूप) एक फ़ाइल फ़ॉर्मेट है जो ISO/IEC 14496-12:2004 पर आधारित है, जो QuickTime फ़ाइल फ़ॉर्मेट पर आधारित है लेकिन प्रारम्भिक ऑब्जेक्ट डिस्क्रिप्टर (IOD) और अन्य MPEG सुविधाओं के समर्थन को औपचारिक रूप से निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/video/mp4/) देखें। |
| static readonly [Webm](../../groupdocs.conversion.filetypes/videofiletype/webm) | .webm एक्सटेंशन वाली फ़ाइल एक वीडियो फ़ाइल है जो ओपन, royalty-free WebM फ़ाइल फ़ॉर्मेट पर आधारित है। इसे वेब पर वीडियो साझा करने के लिए डिज़ाइन किया गया है और यह वीडियो और ऑडियो फ़ॉर्मेट सहित फ़ाइल कंटेनर संरचना को परिभाषित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/video/webm//) देखें। |
| static readonly [Wmv](../../groupdocs.conversion.filetypes/videofiletype/wmv) | Windows Media Video माइक्रोसॉफ्ट द्वारा विकसित संकुचित वीडियो फ़ॉर्मेट है। Society of Motion Picture and Television Engineers (SMPTE) द्वारा मानकीकरण के बाद, WMV अब एक ओपन स्टैंडर्ड फ़ॉर्मेट माना जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/video/wmv/) देखें। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
