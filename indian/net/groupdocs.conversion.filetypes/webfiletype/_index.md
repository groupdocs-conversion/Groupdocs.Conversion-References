---
title: WebFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: वेब दस्तवेज़ं क परभषत करत है नम्न फ़इल प्रकर शमल हैं Xml./webfiletype/xmlJson./webfiletype/jsonHtml./webfiletype/htmlHtm./webfiletype/htmMht./webfiletype/mhtMhtml./webfiletype/mhtmlChm./webfiletype/chm
type: docs
weight: 1080
url: /hi/net/groupdocs.conversion.filetypes/webfiletype/
---
## WebFileType class

वेब दस्तावेज़ों को परिभाषित करता है। निम्न फ़ाइल प्रकार शामिल हैं: [`Xml`](./xml)[`Json`](./json)[`Html`](./html)[`Htm`](./htm)[`Mht`](./mht)[`Mhtml`](./mhtml)[`Chm`](./chm)

```csharp
public sealed class WebFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WebFileType](webfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| [explicit operator](../../groupdocs.conversion.filetypes/webfiletype/op_explicit) | DataFileType को WebFileType में स्पष्ट रूप से बदलें |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [Chm](../../groupdocs.conversion.filetypes/webfiletype/chm) | CHM फ़ाइल स्वरूप Microsoft HTML सहायता फ़ाइल का प्रतिनिधित्व करता है जिसमें HTML पृष्ठों का संग्रह होता है। यह सहायता दस्तावेज़ के विभिन्न हिस्सों में विषयों और नेविगेशन को त्वरित रूप से एक्सेस करने के लिए एक इंडेक्स प्रदान करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/web/chm) . |
| static readonly [Htm](../../groupdocs.conversion.filetypes/webfiletype/htm) | एचटीएम (हाइपर टेक्स्ट मार्कअप लैंग्वेज) ब्राउज़रों में प्रदर्शन के लिए बनाए गए वेब पेजों का विस्तार है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/web/html) . |
| static readonly [Html](../../groupdocs.conversion.filetypes/webfiletype/html) | HTML (हाइपर टेक्स्ट मार्कअप लैंग्वेज) ब्राउज़रों में प्रदर्शन के लिए बनाए गए वेब पेजों का विस्तार है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.conversion.filetypes/webfiletype/json) | JSON (जावास्क्रिप्ट ऑब्जेक्ट नोटेशन) डेटा साझा करने के लिए एक खुला मानक फ़ाइल स्वरूप है जो डेटा को संग्रहीत और प्रसारित करने के लिए मानव-पठनीय पाठ का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/web/json) . |
| static readonly [Mht](../../groupdocs.conversion.filetypes/webfiletype/mht) | एमएचटीएमएल एक्सटेंशन वाली फाइलें एक वेब पेज संग्रह प्रारूप का प्रतिनिधित्व करती हैं जिसे कई अलग-अलग अनुप्रयोगों द्वारा बनाया जा सकता है। प्रारूप को संग्रह प्रारूप के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक फ़ाइल में सहेजता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/web/mhtml) . |
| static readonly [Mhtml](../../groupdocs.conversion.filetypes/webfiletype/mhtml) | एमएचटीएमएल एक्सटेंशन वाली फाइलें एक वेब पेज संग्रह प्रारूप का प्रतिनिधित्व करती हैं जिसे कई अलग-अलग अनुप्रयोगों द्वारा बनाया जा सकता है। प्रारूप को संग्रह प्रारूप के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक फ़ाइल में सहेजता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/web/mhtml) . |
| static readonly [Xml](../../groupdocs.conversion.filetypes/webfiletype/xml) | XML एक्सटेंसिबल मार्कअप लैंग्वेज के लिए है जो HTML के समान है लेकिन वस्तुओं को परिभाषित करने के लिए टैग का उपयोग करने में भिन्न है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/web/xml) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->