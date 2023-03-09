---
title: AudioFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: ऑडय दस्तवेज़ं क परभषत करत है इसमें नम्न प्रकर शमल हैं Mp3./audiofiletype/mp3  Aac./audiofiletype/aac  Aiff./audiofiletype/aiff  Flac./audiofiletype/flac  M4a./audiofiletype/m4a  Wma./audiofiletype/wma  Ac3./audiofiletype/ac3  Ogg./audiofiletype/ogg  Wav./audiofiletype/wav  ऑडय प्ररूपं के बरे में अधक जनेंयहँhttps//docs.fileformat.com/audio/ .
type: docs
weight: 850
url: /hi/net/groupdocs.conversion.filetypes/audiofiletype/
---
## AudioFileType class

ऑडियो दस्तावेज़ों को परिभाषित करता है इसमें निम्न प्रकार शामिल हैं: [`Mp3`](./mp3) , [`Aac`](./aac) , [`Aiff`](./aiff) , [`Flac`](./flac) , [`M4a`](./m4a) , [`Wma`](./wma) , [`Ac3`](./ac3) , [`Ogg`](./ogg) , [`Wav`](./wav) , ऑडियो प्रारूपों के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/audio/) .

```csharp
public sealed class AudioFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [AudioFileType](audiofiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Aac](../../groupdocs.conversion.filetypes/audiofiletype/aac) | एएसी (उन्नत ऑडियो कोडिंग) डिजिटल ऑडियो कोडिंग मानक को संदर्भित करता है जो हानिकारक ऑडियो संपीड़न के आधार पर ऑडियो फाइलों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/audio/aac/) . |
| static readonly [Ac3](../../groupdocs.conversion.filetypes/audiofiletype/ac3) | .ac3 एक्सटेंशन वाली फाइल एक ऑडियो कोडेक 3 फाइल है, जिसे डॉल्बी लेबोरेटरीज ने पेश किया है। यह एक ऑडियो प्रारूप है जिसमें ऑडियो आउटपुट के छह चैनल तक हो सकते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/audio/ac3/) . |
| static readonly [Aiff](../../groupdocs.conversion.filetypes/audiofiletype/aiff) | AIFF (ऑडियो इंटरचेंज फ़ाइल फ़ॉर्मेट) 1998 में Apple द्वारा विकसित एक असम्पीडित ऑडियो फ़ाइल फ़ॉर्मेट है, लेकिन यह EA IFF 85 पर आधारित है इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/audio/aiff/) . |
| static readonly [Flac](../../groupdocs.conversion.filetypes/audiofiletype/flac) | FLAC (मुक्त दोषरहित ऑडियो कोडेक) Xiph.Org Foundation द्वारा विकसित एक दोषरहित संपीड़न ऑडियो कोडिंग प्रारूप है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/audio/flac/) . |
| static readonly [M4a](../../groupdocs.conversion.filetypes/audiofiletype/m4a) | M4A फ़ाइल स्वरूप AAC (उन्नत ऑडियो कोडिंग) का उपयोग करके बनाई गई एक ऑडियो फ़ाइल है जिसे हानिपूर्ण संपीड़न के रूप में जाना जाता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/audio/m4a/) . |
| static readonly [Mp3](../../groupdocs.conversion.filetypes/audiofiletype/mp3) | .mp3 एक्सटेंशन वाली फ़ाइलें ऑडियो फ़ाइलों के लिए डिजिटल रूप से एन्कोड किए गए फ़ाइल स्वरूप हैं जो औपचारिक रूप से MPEG-1 ऑडियो लेयर III या MPEG-2 ऑडियो लेयर III पर आधारित हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/audio/mp3/) . |
| static readonly [Ogg](../../groupdocs.conversion.filetypes/audiofiletype/ogg) | OGG एक Ogg Vorbis कंप्रेस्ड ऑडियो फ़ाइल है जिसे .ogg एक्सटेंशन के साथ सेव किया जाता है। OGG फ़ाइलों का उपयोग ऑडियो डेटा संग्रहीत करने के लिए किया जाता है और इसमें कलाकार और ट्रैक जानकारी और मेटाडेटा भी शामिल हो सकते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/audio/ogg/) . |
| static readonly [Wav](../../groupdocs.conversion.filetypes/audiofiletype/wav) | WAV, WAVE (वेवफ़ॉर्म ऑडियो फ़ाइल फ़ॉर्मेट) के लिए जाना जाता है, डिजिटल ऑडियो फ़ाइलों को संग्रहीत करने के लिए Microsoft के रिसोर्स इंटरचेंज फ़ाइल फ़ॉर्मेट (RIFF) विनिर्देशन का एक सबसेट है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/audio/ogg/) . |
| static readonly [Wma](../../groupdocs.conversion.filetypes/audiofiletype/wma) | .wma एक्सटेंशन वाली फ़ाइल एक ऑडियो फ़ाइल का प्रतिनिधित्व करती है जो उन्नत सिस्टम प्रारूप (ASF) प्रारूप में सहेजी जाती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/audio/wma/) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
