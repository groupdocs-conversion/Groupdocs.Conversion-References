---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "Word Processing फ़ाइलों को परिभाषित करता है जो उपयोगकर्ता जानकारी को साधारण टेक्स्ट या रिच टेक्स्ट फ़ॉर्मेट में रखती हैं। साधारण टेक्स्ट फ़ाइल फ़ॉर्मेट में बिना स्वरूपित टेक्स्ट होता है और कोई फ़ॉन्ट या पेज सेटिंग आदि लागू नहीं की जा सकती। इसके विपरीत, रिच टेक्स्ट फ़ाइल फ़ॉर्मेट फ़ॉन्ट प्रकार, शैली, बोल्ड, इटैलिक, अंडरलाइन आदि जैसे स्वरूपण विकल्पों की अनुमति देता है, साथ ही पेज मार्जिन, हेडिंग, बुलेट और नंबर तथा कई अन्य स्वरूपण सुविधाएँ। निम्नलिखित फ़ाइल प्रकार शामिल हैं: Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Word Processing फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ https//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /hi/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

परिभाषित करता है Word Processing फ़ाइलें जो उपयोगकर्ता जानकारी को साधारण टेक्स्ट या रिच टेक्स्ट फ़ॉर्मेट में रखती हैं। एक साधारण टेक्स्ट फ़ाइल फ़ॉर्मेट में बिना फ़ॉर्मेट का टेक्स्ट होता है और कोई फ़ॉन्ट या पेज सेटिंग आदि लागू नहीं हो सकते। इसके विपरीत, एक रिच टेक्स्ट फ़ाइल फ़ॉर्मेट फ़ॉर्मेटिंग विकल्पों की अनुमति देता है जैसे फ़ॉन्ट प्रकार सेट करना, स्टाइल (बोल्ड, इटैलिक, अंडरलाइन, आदि), पेज मार्जिन, हेडिंग, बुलेट और नंबर, और कई अन्य फ़ॉर्मेटिंग सुविधाएँ। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Word Processing फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing) देखें।

```csharp
public sealed class WordProcessingFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | फ़ाइलें जिनका .doc एक्सटेंशन है, माइक्रोसॉफ्ट वर्ड या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न दस्तावेज़ों का प्रतिनिधित्व करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/doc) देखें। |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM फ़ाइलें माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर की उत्पन्न दस्तावेज़ हैं जिनमें मैक्रो चलाने की क्षमता होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/docm) देखें। |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। 2007 में माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ पेश किया गया, इस नए दस्तावेज़ फ़ॉर्मेट की संरचना साधारण बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दी गई। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/docx) देखें। |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT एक्सटेंशन वाली फ़ाइलें टेम्पलेट फ़ाइलें हैं जो माइक्रोसॉफ्ट वर्ड द्वारा आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स के साथ बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dot) देखें। |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM एक्सटेंशन वाली फ़ाइल एक टेम्पलेट फ़ाइल का प्रतिनिधित्व करती है जो माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के साथ बनाई गई है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dotm) देखें। |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | DOTX एक्सटेंशन वाली फ़ाइलें टेम्पलेट फ़ाइलें हैं जो माइक्रोसॉफ्ट वर्ड द्वारा आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स के साथ बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dotx) देखें। |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word Office Open XML WordprocessingML है जो ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत होता है। |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Markdown भाषा डायलैक्ट्स के साथ बनाई गई टेक्स्ट फ़ाइलें .MD या .MARKDOWN फ़ाइल एक्सटेंशन के साथ सहेजी जाती हैं। MD फ़ाइलें साधारण टेक्स्ट फ़ॉर्मेट में सहेजी जाती हैं जो Markdown भाषा का उपयोग करती हैं जिसमें इनलाइन टेक्स्ट प्रतीक शामिल होते हैं, जो यह परिभाषित करते हैं कि टेक्स्ट को कैसे फ़ॉर्मेट किया जा सकता है जैसे इंडेंटेशन, टेबल फ़ॉर्मेटिंग, फ़ॉन्ट, और हेडर। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/md) देखें। |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो वर्ड प्रोसेसिंग एप्लिकेशन द्वारा बनाए गए हैं और OpenDocument टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/odt) देखें। |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT एक्सटेंशन वाली फ़ाइलें टेम्पलेट दस्तावेज़ों का प्रतिनिधित्व करती हैं जो OASIS के OpenDocument मानक फ़ॉर्मेट के अनुपालन में एप्लिकेशन द्वारा उत्पन्न किए गए हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/ott) देखें। |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Microsoft द्वारा प्रस्तुत और दस्तावेज़ीकृत, Rich Text Format (RTF) एक विधि का प्रतिनिधित्व करता है जिससे फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एप्लिकेशन में उपयोग के लिए एन्कोड किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/rtf) देखें। |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT एक्सटेंशन वाली फ़ाइल एक टेक्स्ट दस्तावेज़ का प्रतिनिधित्व करती है जिसमें साधारण टेक्स्ट पंक्तियों के रूप में होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/txt) देखें। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
