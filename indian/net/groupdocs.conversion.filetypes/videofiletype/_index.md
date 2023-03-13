---
title: VideoFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: वडय दस्तवेज़ं क परभषत करत है इसमें नम्न प्रकर शमल हैं Mp4./videofiletype/mp4  Avi./videofiletype/avi  Flv./videofiletype/flv  Mkv./videofiletype/mkv  Mov./videofiletype/mov  Webm./videofiletype/webm  Wmv./videofiletype/wmv  वडय प्ररूपं के बरे में अधक जनेंयहँhttps//docs.fileformat.com/video/ .
type: docs
weight: 1070
url: /hi/net/groupdocs.conversion.filetypes/videofiletype/
---
## VideoFileType class

वीडियो दस्तावेज़ों को परिभाषित करता है इसमें निम्न प्रकार शामिल हैं: [`Mp4`](./mp4) , [`Avi`](./avi) , [`Flv`](./flv) , [`Mkv`](./mkv) , [`Mov`](./mov) , [`Webm`](./webm) , [`Wmv`](./wmv) , वीडियो प्रारूपों के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/video/) .

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
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल स्वरूप |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | वर्तमान वस्तु की तुलना अन्य से करता है। |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | स्ट्रिंग प्रतिनिधित्व |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Avi](../../groupdocs.conversion.filetypes/videofiletype/avi) | AVI फ़ाइल स्वरूप एक ऑडियो वीडियो मल्टीमीडिया कंटेनर फ़ाइल स्वरूप है जिसे Microsoft द्वारा पेश किया गया था। यह XVid और DivX जैसे कई कोडेक्स (कोडर्स/डिकोडर्स) का उपयोग करके बनाए गए और संपीड़ित ऑडियो और वीडियो डेटा को रखता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/video/avi/) . |
| static readonly [Flv](../../groupdocs.conversion.filetypes/videofiletype/flv) | FLV (फ्लैश वीडियो) .flv एक्सटेंशन के साथ एक कंटेनर फ़ाइल स्वरूप है। FLV का उपयोग Adobe Flash Player या Adobe Air का उपयोग करके इंटरनेट पर ऑडियो/वीडियो सामग्री वितरित करने के लिए किया जाता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/video/flv/) . |
| static readonly [Mkv](../../groupdocs.conversion.filetypes/videofiletype/mkv) | MKV (Matroska Video) MOV और AVI प्रारूप के समान एक मल्टीमीडिया कंटेनर है, लेकिन यह एक ही फ़ाइल में एक से अधिक ऑडियो और उपशीर्षक ट्रैक का समर्थन करता है। MKV फ़ाइल वीडियो के लिए उपयोग किया जाने वाला Matroska मल्टीमीडिया कंटेनर प्रारूप है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/video/mkv/) . |
| static readonly [Mov](../../groupdocs.conversion.filetypes/videofiletype/mov) | MOV या QuickTime फ़ाइल स्वरूप एक मल्टीमीडिया कंटेनर है जिसे Apple द्वारा विकसित किया गया है: इसमें एक या अधिक ट्रैक होते हैं, प्रत्येक ट्रैक में एक विशेष प्रकार का डेटा होता है जैसे कि वीडियो, ऑडियो, टेक्स्ट, आदि। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/video/mov/) . |
| static readonly [Mp4](../../groupdocs.conversion.filetypes/videofiletype/mp4) | MP4 (MPEG-4 भाग 14 के लिए संक्षिप्त) ISO/IEC 14496-12:2004 पर आधारित एक फ़ाइल स्वरूप है जो QuickTime फ़ाइल स्वरूप पर आधारित है लेकिन औपचारिक रूप से प्रारंभिक ऑब्जेक्ट डिस्क्रिप्टर (IOD) और अन्य MPEG सुविधाओं के लिए समर्थन निर्दिष्ट करता है। जानें इस फ़ाइल स्वरूप के बारे में अधिक[यहाँ](https://docs.fileformat.com/video/mp4/) . |
| static readonly [Webm](../../groupdocs.conversion.filetypes/videofiletype/webm) | .webm एक्सटेंशन वाली फ़ाइल खुले, रॉयल्टी-मुक्त WebM फ़ाइल स्वरूप पर आधारित एक वीडियो फ़ाइल है। यह वेब पर वीडियो साझा करने के लिए डिज़ाइन किया गया है और वीडियो और ऑडियो प्रारूपों सहित फ़ाइल कंटेनर संरचना को परिभाषित करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/video/webm//) . |
| static readonly [Wmv](../../groupdocs.conversion.filetypes/videofiletype/wmv) | उन्नत सिस्टम प्रारूप (ASF) एक डिजिटल मल्टीमीडिया कंटेनर है जिसे मुख्य रूप से मीडिया स्ट्रीम को संग्रहीत करने और प्रसारित करने के लिए डिज़ाइन किया गया है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/video/wmv/) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
