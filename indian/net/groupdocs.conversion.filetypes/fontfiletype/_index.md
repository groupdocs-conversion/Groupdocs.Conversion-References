---
title: FontFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: फ़न्ट दस्तवेज़ं क परभषत करत है इसमें नम्न प्रकर शमल हैं Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 फ़न्ट प्ररूपं के बरे में अधक जनेंयहँhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /hi/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

फ़ॉन्ट दस्तावेज़ों को परिभाषित करता है इसमें निम्न प्रकार शामिल हैं: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) फ़ॉन्ट प्रारूपों के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/font/) .

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | .cff एक्सटेंशन वाली फाइल एक कॉम्पैक्ट फॉन्ट फॉर्मेट है और इसे पोस्टस्क्रिप्ट टाइप 1 या CIDFont के रूप में भी जाना जाता है। CFF एक फॉन्टसेट के रूप में जानी जाने वाली एक इकाई में एक साथ कई फोंट को स्टोर करने के लिए एक कंटेनर के रूप में कार्य करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | .eot एक्सटेंशन वाली फ़ाइल एक ओपन टाइप फ़ॉन्ट है जो दस्तावेज़ में एम्बेड किया गया है। ये ज्यादातर वेब फाइलों जैसे वेब पेज में उपयोग किए जाते हैं। यह Microsoft द्वारा बनाया गया था और PowerPoint प्रस्तुति .pps फ़ाइल सहित Microsoft उत्पादों द्वारा समर्थित है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | .otf एक्सटेंशन वाली फ़ाइल ओपनटाइप फ़ॉन्ट प्रारूप को संदर्भित करती है। OTF फ़ॉन्ट प्रारूप अधिक मापनीय है और डिजिटल टाइपोग्राफी के लिए TTF प्रारूपों की मौजूदा विशेषताओं का विस्तार करता है। Microsoft और Adobe द्वारा विकसित, OTF पोस्टस्क्रिप्ट और ट्रू टाइप फ़ॉन्ट स्वरूपों की सुविधाओं को जोड़ती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | .ttf एक्सटेंशन वाली फ़ाइल ट्रू टाइप विनिर्देशों फ़ॉन्ट तकनीक पर आधारित फ़ॉन्ट फ़ाइलों का प्रतिनिधित्व करती है। शुरुआत में इसे Mac OS के लिए Apple Computer, Inc द्वारा डिज़ाइन और लॉन्च किया गया था और बाद में इसे Microsoft द्वारा Windows OS के लिए अपनाया गया था। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | टाइप 1 फोंट एक बहिष्कृत एडोब तकनीक है जिसका व्यापक रूप से डेस्कटॉप आधारित प्रकाशन सॉफ्टवेयर और प्रिंटर में उपयोग किया जाता था जो पोस्टस्क्रिप्ट का उपयोग कर सकते थे। हालांकि टाइप 1 फोंट कई आधुनिक प्लेटफॉर्म, वेब ब्राउज़र और मोबाइल ऑपरेटिंग सिस्टम में समर्थित नहीं हैं, लेकिन ये अभी भी कुछ ऑपरेटिंग सिस्टम में समर्थित हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | .woff एक्सटेंशन वाली फाइल वेब ओपन फॉन्ट फॉर्मेट (WOFF) पर आधारित एक वेब फॉन्ट फाइल है। इसमें ट्रू टाइप (.TTF) या ओपन टाइप (.OTT) फ़ॉन्ट प्रकारों पर आधारित प्रारूप-विशिष्ट कंप्रेस्ड कंटेनर है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | .woff एक्सटेंशन वाली फाइल वेब ओपन फॉन्ट फॉर्मेट (WOFF) पर आधारित एक वेब फॉन्ट फाइल है। इसमें ट्रू टाइप (.TTF) या ओपन टाइप (.OTT) फ़ॉन्ट प्रकारों पर आधारित प्रारूप-विशिष्ट कंप्रेस्ड कंटेनर है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/font/woff/) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
