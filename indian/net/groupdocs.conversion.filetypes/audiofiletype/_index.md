---
title: "AudioFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "Audio दस्तावेज़ को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं Mp3./audiofiletype/mp3 Aac./audiofiletype/aac Aiff./audiofiletype/aiff Flac./audiofiletype/flac M4a./audiofiletype/m4a Wma./audiofiletype/wma Ac3./audiofiletype/ac3 Ogg./audiofiletype/ogg Wav./audiofiletype/wav। ऑडियो फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ https//docs.fileformat.com/audio/ देखें।"
type: docs
weight: 1060
url: /hi/net/groupdocs.conversion.filetypes/audiofiletype/
---
## AudioFileType class

Audio दस्तावेज़ को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं: [`Mp3`](./mp3), [`Aac`](./aac), [`Aiff`](./aiff), [`Flac`](./flac), [`M4a`](./m4a), [`Wma`](./wma), [`Ac3`](./ac3), [`Ogg`](./ogg), [`Wav`](./wav)। ऑडियो फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/) देखें।

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
| static readonly [Aac](../../groupdocs.conversion.filetypes/audiofiletype/aac) | AAC (Advanced Audio Coding) डिजिटल ऑडियो कोडिंग मानक को दर्शाता है जो लॉसी ऑडियो संपीड़न पर आधारित ऑडियो फ़ाइलों का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/aac/) देखें। |
| static readonly [Ac3](../../groupdocs.conversion.filetypes/audiofiletype/ac3) | .ac3 एक्सटेंशन वाली फ़ाइल Audio Codec 3 फ़ाइल है, जिसे Dolby Laboratories ने प्रस्तुत किया था। यह एक ऑडियो फ़ॉर्मेट है जो अधिकतम छह चैनलों की ऑडियो आउटपुट रख सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/ac3/) देखें। |
| static readonly [Aiff](../../groupdocs.conversion.filetypes/audiofiletype/aiff) | AIFF (Audio Interchange File Format) एक अनकम्प्रेस्ड ऑडियो फ़ाइल फ़ॉर्मेट है जिसे Apple ने 1998 में विकसित किया था, लेकिन यह EA IFF 85 पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/aiff/) देखें। |
| static readonly [Flac](../../groupdocs.conversion.filetypes/audiofiletype/flac) | FLAC (Free Lossless Audio Codec) एक लॉसलेस संपीड़न ऑडियो कोडिंग फ़ॉर्मेट है जिसे Xiph.Org Foundation ने विकसित किया है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/flac/) देखें। |
| static readonly [M4a](../../groupdocs.conversion.filetypes/audiofiletype/m4a) | M4A फ़ाइल फ़ॉर्मेट एक ऑडियो फ़ाइल है जो AAC (Advanced Audio Coding) का उपयोग करके बनाई गई है, जिसे लॉसी संपीड़न के रूप में जाना जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/m4a/) देखें। |
| static readonly [Mp3](../../groupdocs.conversion.filetypes/audiofiletype/mp3) | .mp3 एक्सटेंशन वाली फ़ाइलें डिजिटल रूप से एन्कोडेड ऑडियो फ़ाइल फ़ॉर्मेट हैं जो औपचारिक रूप से MPEG-1 Audio Layer III या MPEG-2 Audio Layer III पर आधारित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/mp3/) देखें। |
| static readonly [Ogg](../../groupdocs.conversion.filetypes/audiofiletype/ogg) | OGG एक Ogg Vorbis संकुचित ऑडियो फ़ाइल है जिसे .ogg एक्सटेंशन के साथ सहेजा जाता है। OGG फ़ाइलें ऑडियो डेटा संग्रहीत करने के लिए उपयोग की जाती हैं और इनमें कलाकार, ट्रैक जानकारी और मेटाडेटा भी शामिल हो सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/ogg/) देखें। |
| static readonly [Wav](../../groupdocs.conversion.filetypes/audiofiletype/wav) | WAV, जिसे WAVE (Waveform Audio File Format) के नाम से जाना जाता है, माइक्रोसॉफ्ट के रिसोर्स इंटरचेन्ज फ़ाइल फ़ॉर्मेट (RIFF) विनिर्देशन का एक उपसमुच्चय है जो डिजिटल ऑडियो फ़ाइलों को संग्रहीत करने के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/ogg/) देखें। |
| static readonly [Wma](../../groupdocs.conversion.filetypes/audiofiletype/wma) | .wma एक्सटेंशन वाली फ़ाइल एक ऑडियो फ़ाइल को दर्शाती है जो Advanced Systems Format (ASF) फ़ॉर्मेट में सहेजी गई है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/audio/wma/) देखें। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
