---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "कम्प्रेशन फ़ॉर्मेट को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. अधिक जानकारी के लिए यहाँ कम्प्रेशन फ़ॉर्मेट देखें https//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /hi/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

कम्प्रेशन फ़ॉर्मेट को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). अधिक जानकारी के लिए कम्प्रेशन फ़ॉर्मेट [यहाँ](https://docs.fileformat.com/compression/) देखें।

```csharp
public sealed class CompressionFileType : FileType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | फ़ाइल प्रकार विवरण |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | फ़ाइल एक्सटेंशन |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | फ़ाइल परिवार |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | फ़ाइल फ़ॉर्मेट |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | परिभाषित करता है कि फ़ॉर्मेट एक ही आर्काइव में कई फ़ाइलें/फ़ोल्डर का समर्थन करता है या नहीं। |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | .aar एक्सटेंशन वाली फ़ाइल Apple Archive है, जो macOS के साथ फ़ाइलों और फ़ोल्डरों को समूहित करने के लिए Apple द्वारा प्रदान किया जाता है। प्रत्येक प्रविष्टि अलग से संकुचित होती है, अक्सर LZFSE के साथ। |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | .alz एक्सटेंशन वाली फ़ाइल ALZip आर्काइव है, जो ESTsoft द्वारा विकसित फ़ॉर्मेट है और दक्षिण कोरिया में व्यापक रूप से उपयोग होता है। प्रविष्टियों को पासवर्ड से व्यक्तिगत रूप से एन्क्रिप्ट किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी [यहाँ](https://docs.fileformat.com/compression/alz/) प्राप्त करें। |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 वह संकुचित फ़ाइलें हैं जो BZIP2 ओपन सोर्स कम्प्रेशन विधि का उपयोग करके बनाई जाती हैं, मुख्यतः UNIX या Linux सिस्टम पर। यह एकल फ़ाइल के संकुचन के लिए उपयोग होती है और कई फ़ाइलों के आर्काइविंग के लिए नहीं है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी [यहाँ](https://docs.fileformat.com/compression/bz2/) प्राप्त करें। |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab एक्सटेंशन वाली फ़ाइल Windows कैबिनेट फ़ाइल है, जो सिस्टम फ़ाइलों की श्रेणी में आती है। यह फ़ाइल Microsoft Windows के उन संस्करणों में आर्काइव फ़ॉर्मेट में सहेजी जाती है जो संकुचित डेटा एल्गोरिदम जैसे LZX, Quantum, और ZIP का समर्थन करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी [यहाँ](https://docs.fileformat.com/system/cab/) प्राप्त करें। |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio एक सामान्य फ़ाइल आर्काइवर यूटिलिटी और इसका संबंधित फ़ाइल फ़ॉर्मेट है। यह मुख्यतः Unix-समतुल्य कंप्यूटर ऑपरेटिंग सिस्टम पर स्थापित होता है। |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ फ़ाइल एक संकुचित आर्काइव है जो मानक gzip (GNU zip) कम्प्रेशन एल्गोरिदम का उपयोग करके बनाई जाती है। इसमें कई संकुचित फ़ाइलें, डायरेक्टरी और फ़ाइल स्टब्स हो सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी [यहाँ](https://docs.fileformat.com/compression/gz/) प्राप्त करें। |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip फ़ाइल एक संकुचित आर्काइव है जो मानक gzip (GNU zip) कम्प्रेशन एल्गोरिदम का उपयोग करके बनाई जाती है। इसमें कई संकुचित फ़ाइलें, डायरेक्टरी और फ़ाइल स्टब्स हो सकते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी [यहाँ](https://docs.fileformat.com/compression/gz/) प्राप्त करें। |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | .iso एक्सटेंशन वाली फ़ाइल एक अनकम्प्रेस्ड आर्काइव डिस्क इमेज फ़ाइल है जो CD या DVD जैसे ऑप्टिकल डिस्क पर संपूर्ण डेटा की सामग्री को दर्शाती है। ISO-9660 मानक पर आधारित, ISO इमेज फ़ाइल फ़ॉर्मेट में डिस्क डेटा के साथ फ़ाइल‑सिस्टम जानकारी भी संग्रहीत होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | .lzh और .lha एक्सटेंशन वाली फ़ाइल आमतौर पर आर्काइव कम्प्रेशन फ़ाइल फ़ॉर्मेट से संबंधित होती है। यह फ़ॉर्मेट ZIP, RAR आदि जैसे अन्य फ़ाइल कम्प्रेशन फ़ॉर्मेट के समान है। इन फ़ॉर्मेट्स का मुख्य उद्देश्य फ़ाइलों का आकार घटाकर आसानी से भेजना और उन्हें संकुचित रूप में एक साथ रखना है। |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz एक्सटेंशन वाली फ़ाइल Lzip द्वारा बनाई गई एक संकुचित आर्काइव फ़ाइल है, जो एक मुफ्त कमांड‑लाइन टूल है। यह फ़ाइलें application/lzip मीडिया टाइप रखती हैं और BZ2 की तुलना में उच्च कम्प्रेशन अनुपात प्रदान करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | .lz4 एक्सटेंशन वाली फ़ाइल उन एप्लिकेशन/यूटिलिटीज़ द्वारा बनाई गई संकुचित आर्काइव फ़ाइल है जो LZ4 कम्प्रेशन का समर्थन करती हैं। LZ4 एल्गोरिद्म गति और कम्प्रेशन अनुपात के बीच संतुलन पर केंद्रित है। LZ4 कमांड‑लाइन यूटिलिटी से संकुचित आर्काइव बनाए जा सकते हैं और उसी से डिकम्प्रेस भी किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma एक्सटेंशन वाली फ़ाइल LZMA (Lempel‑Ziv‑Markov chain Algorithm) कम्प्रेशन विधि का उपयोग करके बनाई गई संकुचित आर्काइव फ़ाइल है। ये मुख्यतः Unix ऑपरेटिंग सिस्टम पर पाई जाती हैं और ZIP जैसी अन्य कम्प्रेशन एल्गोरिद्म के समान फ़ाइल आकार को कम करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar एक्सटेंशन वाली फ़ाइलें ऐसी आर्काइव फ़ाइलें हैं जो जानकारी को संकुचित या सामान्य रूप में संग्रहीत करने के लिए बनाई जाती हैं। RAR, Roshal ARchive फ़ाइल फ़ॉर्मेट का संक्षिप्त रूप है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z एक आर्काइविंग फ़ॉर्मेट है जो फ़ाइलों और फ़ोल्डरों को उच्च कम्प्रेशन अनुपात के साथ संकुचित करता है। यह ओपन‑सोर्स आर्किटेक्चर पर आधारित है, जिससे कोई भी कम्प्रेशन और एन्क्रिप्शन एल्गोरिद्म उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar एक्सटेंशन वाली फ़ाइलें Unix‑आधारित यूटिलिटी द्वारा बनाई गई आर्काइव हैं, जो एक या अधिक फ़ाइलों को इकट्ठा करती हैं। कई फ़ाइलें अनकम्प्रेस्ड रूप में संग्रहीत की जाती हैं और फ़ाइलों तथा फ़ोल्डरों को आर्काइव में जोड़ने का समर्थन करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | एक uuencoded आर्काइव वह फ़ाइल या फ़ाइलों का संग्रह है जिसे Unix‑to‑Unix एन्कोडिंग स्कीम (uuencode) का उपयोग करके एन्कोड किया गया है। यह एन्कोडिंग विधि बाइनरी डेटा को टेक्स्ट फ़ॉर्मेट में बदल देती है, जिससे केवल टेक्स्ट को सपोर्ट करने वाले चैनलों, जैसे ई‑मेल, पर फ़ाइलें भेजना आसान हो जाता है। |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | .wim एक्सटेंशन वाली फ़ाइल Windows Imaging Format आर्काइव है, जो माइक्रोसॉफ्ट द्वारा Windows को डिप्लॉय करने के लिए उपयोग की जाने वाली फ़ाइल‑आधारित डिस्क इमेज है। एक एकल आर्काइव में एक या अधिक इमेज होते हैं और प्रत्येक फ़ाइल को केवल एक बार संग्रहीत किया जाता है, चाहे कितनी भी इमेज उसे संदर्भित करें। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | .xar एक्सटेंशन वाली फ़ाइल eXtensible ARchive है, एक फ़ॉर्मेट जो संकुचित XML के रूप में संग्रहीत सामग्री तालिका के आसपास निर्मित है। यह macOS इंस्टॉलर पैकेज वितरित करने के लिए उपयोग होती है और प्रत्येक प्रविष्टि को स्वतंत्र रूप से संकुचित रखती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ एक संकुचित फ़ाइल फ़ॉर्मेट है जो LZMA2 कम्प्रेशन एल्गोरिद्म का उपयोग करता है। इसे लोकप्रिय gzip और bzip2 फ़ॉर्मेट के विकल्प के रूप में डिज़ाइन किया गया था, और यह इन पुराने मानकों की तुलना में कई लाभ प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Z फ़ाइल एक प्रकार की फ़ाइलों की श्रेणी है जो UNIX संकुचित डेटा फ़ाइलों से संबंधित है। संकुचित Unix फ़ाइलें Z फ़ाइल का सबसे लोकप्रिय और व्यापक रूप से उपयोग किया जाने वाला एक्सटेंशन प्रकार हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/compression/z/) देखें। |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip एक्सटेंशन वाली फ़ाइल एक आर्काइव है जो एक या अधिक फ़ाइलें या डायरेक्टरी रख सकती है। आर्काइव में शामिल फ़ाइलों पर संपीड़न लागू किया जा सकता है ताकि ZIP फ़ाइल का आकार कम हो सके। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/compression/zip/) देखें। |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | ZST फ़ाइल एक संकुचित फ़ाइल है जो Zstandard (zstd) संपीड़न एल्गोरिद्म द्वारा उत्पन्न होती है। यह एक लॉसलेस संपीड़न से बनाई गई संकुचित फ़ाइल है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/compression/zst/) देखें। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
