---
title: WordProcessingFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: उन वर्ड प्रसेसंग फइलं क परभषत करत है जनमें सदे पठ य समृद्ध पठ प्ररूप में उपयगकर्त जनकर हत है एक सद पठ फ़इल प्ररूप में अस्वरूपत पठ हत है और कई फ़न्ट य पृष्ठ सेटंग आद लगू नहं कय ज सकत है इसके वपरत एक समृद्ध पठ फ़इल प्ररूप स्वरूपण वकल्प जैसे क फ़न्ट प्रकर शैल बल्ड इटैलक अंडरलइन आद पृष्ठ हशए शर्षक बुलेट और संख्यएँ और कई अन्य स्वरूपण सुवधओं क अनुमत देत है में नम्न फ़इल प्रकर शमल हैं Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . वर्ड प्रसेसंग प्ररूपं के बरे में अधक जनेंयहँhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /hi/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

उन वर्ड प्रोसेसिंग फाइलों को परिभाषित करता है जिनमें सादे पाठ या समृद्ध पाठ प्रारूप में उपयोगकर्ता जानकारी होती है। एक सादा पाठ फ़ाइल प्रारूप में अस्वरूपित पाठ होता है और कोई फ़ॉन्ट या पृष्ठ सेटिंग आदि लागू नहीं किया जा सकता है। इसके विपरीत, एक समृद्ध पाठ फ़ाइल प्रारूप स्वरूपण विकल्प जैसे कि फ़ॉन्ट प्रकार, शैली (बोल्ड, इटैलिक, अंडरलाइन, आदि), पृष्ठ हाशिए, शीर्षक, बुलेट और संख्याएँ, और कई अन्य स्वरूपण सुविधाओं की अनुमति देता है। में निम्न फ़ाइल प्रकार शामिल हैं: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . वर्ड प्रोसेसिंग प्रारूपों के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing) .

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | .doc एक्सटेंशन वाली फ़ाइलें Microsoft Word या बाइनरी फ़ाइल स्वरूप में अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा उत्पन्न दस्तावेज़ों का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM फ़ाइलें Microsoft Word 2007 या उच्चतर जेनरेट किए गए दस्तावेज़ हैं जिनमें मैक्रोज़ चलाने की क्षमता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है। Microsoft Office 2007 की रिलीज़ के साथ 2007 से पेश किया गया, इस नए दस्तावेज़ प्रारूप की संरचना को सादे बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दिया गया था। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | .DOT एक्सटेंशन वाली फाइलें Microsoft Word द्वारा बनाई गई टेम्प्लेट फाइलें हैं, जिनमें आगे DOC या DOCX फ़ाइलों की पीढ़ी के लिए पूर्व-स्वरूपित सेटिंग्स होती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | DOTM एक्सटेंशन वाली फ़ाइल Microsoft Word 2007 या उच्चतर के साथ बनाई गई टेम्पलेट फ़ाइल का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | डीओटीएक्स एक्सटेंशन वाली फाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्पलेट फाइलें हैं जो आगे की डीओसीएक्स फाइलों की पीढ़ी के लिए पूर्व-स्वरूपित सेटिंग्स हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | मार्कडाउन भाषा बोलियों के साथ बनाई गई टेक्स्ट फ़ाइलें .MD या .MARKDOWN फ़ाइल एक्सटेंशन के साथ सहेजी जाती हैं। एमडी फाइलें सादे पाठ प्रारूप में सहेजी जाती हैं जो मार्कडाउन भाषा का उपयोग करती हैं जिसमें इनलाइन टेक्स्ट प्रतीक भी शामिल होते हैं, यह परिभाषित करते हैं कि इंडेंटेशन, टेबल फॉर्मेटिंग, फोंट और हेडर जैसे टेक्स्ट को कैसे स्वरूपित किया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT फाइलें वर्ड प्रोसेसिंग एप्लिकेशन के साथ बनाए गए दस्तावेज़ हैं जो OpenDocument टेक्स्ट फ़ाइल स्वरूप पर आधारित हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | OTT एक्सटेंशन वाली फ़ाइलें OASIS के OpenDocument मानक प्रारूप के अनुपालन में एप्लिकेशन द्वारा उत्पन्न टेम्प्लेट दस्तावेज़ों का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | माइक्रोसॉफ्ट द्वारा प्रस्तुत और प्रलेखित, रिच टेक्स्ट फॉर्मेट (RTF) अनुप्रयोगों के भीतर उपयोग के लिए स्वरूपित पाठ और ग्राफिक्स को एन्कोडिंग की एक विधि का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | .TXT एक्सटेंशन वाली फ़ाइल एक टेक्स्ट दस्तावेज़ का प्रतिनिधित्व करती है जिसमें लाइनों के रूप में सादा पाठ होता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/txt) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
