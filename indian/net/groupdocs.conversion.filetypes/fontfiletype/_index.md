---
title: "FontFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "फ़ॉन्ट दस्तावेज़ परिभाषित करता है निम्नलिखित प्रकार Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 फ़ॉन्ट फ़ॉर्मेट के बारे में अधिक जानें यहाँhttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /hi/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

फ़ॉन्ट दस्तावेज़ परिभाषित करता है निम्नलिखित प्रकार: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) फ़ॉन्ट फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FontFileType](fontfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | एक फ़ाइल जिसका .cff एक्सटेंशन है, वह एक कॉम्पैक्ट फ़ॉन्ट फ़ॉर्मेट है और इसे पोस्टस्क्रिप्ट टाइप 1 या CIDFont के रूप में भी जाना जाता है। CFF एक कंटेनर के रूप में कार्य करता है जो कई फ़ॉन्ट को एक ही इकाई में संग्रहीत करता है, जिसे FontSet कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | एक फ़ाइल जिसका .eot एक्सटेंशन है, वह एक OpenType फ़ॉन्ट है जो किसी दस्तावेज़ में एम्बेड किया गया है। ये मुख्यतः वेब फ़ाइलों जैसे वेब पेज में उपयोग होते हैं। इसे माइक्रोसॉफ्ट ने बनाया और माइक्रोसॉफ्ट उत्पादों जैसे PowerPoint प्रस्तुति .pps फ़ाइल में समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | एक फ़ाइल जिसका .otf एक्सटेंशन है, वह OpenType फ़ॉन्ट फ़ॉर्मेट को दर्शाता है। OTF फ़ॉर्मेट अधिक स्केलेबल है और डिजिटल टाइपोग्राफी के लिए TTF फ़ॉर्मेट की मौजूदा सुविधाओं का विस्तार करता है। माइक्रोसॉफ्ट और Adobe द्वारा विकसित, OTF पोस्टस्क्रिप्ट और TrueType फ़ॉन्ट फ़ॉर्मेट की विशेषताओं को मिलाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | एक फ़ाइल जिसका .ttf एक्सटेंशन है, वह TrueType विशिष्टताओं पर आधारित फ़ॉन्ट फ़ाइलों को दर्शाता है। इसे मूल रूप से Apple Computer, Inc द्वारा मैक OS के लिए डिज़ाइन और लॉन्च किया गया था और बाद में माइक्रोसॉफ्ट द्वारा Windows OS के लिए अपनाया गया। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1 फ़ॉन्ट एक पुरानी Adobe तकनीक है जो डेस्कटॉप प्रकाशन सॉफ़्टवेयर और प्रिंटरों में व्यापक रूप से उपयोग होती थी जो PostScript का उपयोग कर सकते थे। हालांकि Type 1 फ़ॉन्ट कई आधुनिक प्लेटफ़ॉर्म, वेब ब्राउज़र और मोबाइल ऑपरेटिंग सिस्टम में समर्थित नहीं हैं, लेकिन कुछ ऑपरेटिंग सिस्टम में अभी भी समर्थित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | एक फ़ाइल जिसका .woff एक्सटेंशन है, वह Web Open Font Format (WOFF) पर आधारित वेब फ़ॉन्ट फ़ाइल है। इसमें TrueType (.TTF) या OpenType (.OTT) फ़ॉन्ट प्रकारों पर आधारित फ़ॉर्मेट-विशिष्ट संकुचित कंटेनर होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | एक फ़ाइल जिसका .woff एक्सटेंशन है, वह Web Open Font Format (WOFF) पर आधारित वेब फ़ॉन्ट फ़ाइल है। इसमें TrueType (.TTF) या OpenType (.OTT) फ़ॉन्ट प्रकारों पर आधारित फ़ॉर्मेट-विशिष्ट संकुचित कंटेनर होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/font/woff/). |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
