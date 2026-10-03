---
title: "AudioFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ऑडियो दस्तावेज़ को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं          ऑडियो फ़ॉर्मेट के बारे में अधिक जानें यहाँ।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

ऑडियो दस्तावेज़ को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं: , , , , , , , , , ऑडियो फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Mp3](#Mp3) | .mp3 एक्सटेंशन वाली फ़ाइलें ऑडियो फ़ाइलों के लिए डिजिटल रूप से एन्कोडेड फ़ाइल फ़ॉर्मेट हैं जो औपचारिक रूप से MPEG-1 ऑडियो लेयर III या MPEG-2 ऑडियो लेयर III पर आधारित हैं। |
|
|  | [Aac](#Aac) | AAC (एडवांस्ड ऑडियो कोडिंग) डिजिटल ऑडियो कोडिंग मानक को दर्शाता है जो लॉसी ऑडियो संपीड़न पर आधारित ऑडियो फ़ाइलों का प्रतिनिधित्व करता है। |
|
|  | [Aiff](#Aiff) | AIFF (Audio Interchange File Format) एक अनकम्प्रेस्ड ऑडियो फ़ाइल फ़ॉर्मेट है जिसे Apple ने 1998 में विकसित किया, लेकिन यह EA IFF 85 पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/aiff/). |
|
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) एक लॉसलेस कंप्रेशन ऑडियो कोडिंग फ़ॉर्मेट है जिसे Xiph.Org Foundation ने विकसित किया। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/flac/). |
|
|  | [M4a](#M4a) | M4A फ़ाइल फ़ॉर्मेट एक ऑडियो फ़ाइल है जो AAC (Advanced Audio Coding) का उपयोग करके बनाई गई है, जो लॉसी कंप्रेशन के रूप में जानी जाती है। |
|
|  | [Wma](#Wma) | .wma एक्सटेंशन वाली फ़ाइल एक ऑडियो फ़ाइल को दर्शाती है जो Advanced Systems Format (ASF) फ़ॉर्मेट में सहेजी गई है। |
|
|  | [Ac3](#Ac3) | .ac3 एक्सटेंशन वाली फ़ाइल एक Audio Codec 3 फ़ाइल है, जिसे Dolby Laboratories ने प्रस्तुत किया। |
|
|  | [Ogg](#Ogg) | OGG एक Ogg Vorbis कंप्रेस्ड ऑडियो फ़ाइल है जो .ogg एक्सटेंशन के साथ सहेजी गई है। |
|
|  | [Wav](#Wav) | WAV, जिसे WAVE (Waveform Audio File Format) के नाम से जाना जाता है, Microsoft\u2019s Resource Interchange File Format (RIFF) विनिर्देश का एक उपसमुच्चय है जो डिजिटल ऑडियो फ़ाइलों को संग्रहीत करने के लिए उपयोग होता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


.mp3 एक्सटेंशन वाली फ़ाइलें डिजिटल रूप से एन्कोडेड फ़ाइल फ़ॉर्मेट हैं जो ऑडियो फ़ाइलों के लिए हैं और औपचारिक रूप से MPEG-1 Audio Layer III या MPEG-2 Audio Layer III पर आधारित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/mp3/).


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) एक डिजिटल ऑडियो कोडिंग मानक को दर्शाता है जो लॉसी ऑडियो कंप्रेशन पर आधारित ऑडियो फ़ाइलों को प्रस्तुत करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/aac/).


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF (Audio Interchange File Format) एक अनकम्प्रेस्ड ऑडियो फ़ाइल फ़ॉर्मेट है जिसे Apple ने 1998 में विकसित किया, लेकिन यह EA IFF 85 पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/aiff/).


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) एक लॉसलेस कंप्रेशन ऑडियो कोडिंग फ़ॉर्मेट है जिसे Xiph.Org Foundation ने विकसित किया। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/flac/).


### M4a {#M4a}
```
public static final AudioFileType M4a
```


M4A फ़ाइल फ़ॉर्मेट एक ऑडियो फ़ाइल है जो AAC (Advanced Audio Coding) का उपयोग करके बनाई गई है, जो लॉसी कंप्रेशन के रूप में जानी जाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/m4a/).


### Wma {#Wma}
```
public static final AudioFileType Wma
```


.wma एक्सटेंशन वाली फ़ाइल एक ऑडियो फ़ाइल को दर्शाती है जो Advanced Systems Format (ASF) फ़ॉर्मेट में सहेजी गई है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/wma/).


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


.ac3 एक्सटेंशन वाली फ़ाइल एक Audio Codec 3 फ़ाइल है, जिसे Dolby Laboratories ने प्रस्तुत किया। यह एक ऑडियो फ़ॉर्मेट है जो अधिकतम छह चैनलों के ऑडियो आउटपुट को समाहित कर सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/ac3/).


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG एक Ogg Vorbis कंप्रेस्ड ऑडियो फ़ाइल है जो .ogg एक्सटेंशन के साथ सहेजी गई है। OGG फ़ाइलें ऑडियो डेटा संग्रहीत करने के लिए उपयोग की जाती हैं और कलाकार तथा ट्रैक जानकारी और मेटाडेटा भी शामिल कर सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/ogg/).


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, जिसे WAVE (Waveform Audio File Format) के नाम से जाना जाता है, Microsoft\u2019s Resource Interchange File Format (RIFF) विनिर्देश का एक उपसमुच्चय है जो डिजिटल ऑडियो फ़ाइलों को संग्रहीत करने के लिए उपयोग होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/audio/ogg/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
