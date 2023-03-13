---
title: PresentationFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: प्रस्तुतकरण फ़इल स्वरूपं क परभषत करत है ज स्लइड आकृतयं पठ एनमेशन वडय ऑडय और एम्बेडेड वस्तुओं जैसे प्रस्तुत डेट क समयजत करने के लए रकर्ड के संग्रह क संग्रहत करत है में नम्न फ़इल प्रकर शमल हैं Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . प्रस्तुत प्ररूपं के बरे में और जनेंयहँhttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /hi/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

प्रस्तुतीकरण फ़ाइल स्वरूपों को परिभाषित करता है जो स्लाइड, आकृतियों, पाठ, एनिमेशन, वीडियो, ऑडियो और एम्बेडेड वस्तुओं जैसे प्रस्तुति डेटा को समायोजित करने के लिए रिकॉर्ड के संग्रह को संग्रहीत करता है। में निम्न फ़ाइल प्रकार शामिल हैं: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . प्रस्तुति प्रारूपों के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | एफओडीपी एक्सटेंशन वाली फाइलें ओपन डॉक्यूमेंट फ्लैट एक्सएमएल प्रस्तुति का प्रतिनिधित्व करती हैं। प्रस्तुतिकरण फ़ाइल OpenDocument प्रारूप में सहेजी गई, लेकिन मानक .ODP files द्वारा उपयोग किए जाने वाले .ZIP कंटेनर के बजाय समतल XML प्रारूप का उपयोग करके सहेजी गई |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP एक्सटेंशन वाली फ़ाइलें OpenOffice.org द्वारा OASISOpen मानक में प्रयुक्त प्रस्तुति फ़ाइल स्वरूप का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | .OTP एक्सटेंशन वाली फ़ाइलें OASIS OpenDocument मानक प्रारूप में एप्लिकेशन द्वारा बनाई गई प्रस्तुति टेम्प्लेट फ़ाइलों का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | .POT एक्सटेंशन वाली फ़ाइलें PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलों का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | पीओटीएम एक्सटेंशन वाली फाइलें मैक्रोज़ के समर्थन के साथ माइक्रोसॉफ्ट पावरप्वाइंट टेम्पलेट फाइलें हैं। POTM फाइलें PowerPoint 2007 या इसके बाद के संस्करण के साथ बनाई गई हैं और इसमें डिफ़ॉल्ट सेटिंग्स हैं जिनका उपयोग आगे की प्रस्तुति फ़ाइलों को बनाने के लिए किया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | .POTX एक्सटेंशन वाली फाइलें Microsoft PowerPoint टेम्पलेट प्रस्तुतियों का प्रतिनिधित्व करती हैं जो Microsoft PowerPoint 2007 और इसके बाद के संस्करण के साथ बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint स्लाइड शो, फ़ाइलें स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाई गई हैं। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM एक्सटेंशन वाली फ़ाइलें Microsoft PowerPoint 2007 या उच्चतर के साथ बनाए गए मैक्रो-सक्षम स्लाइड शो फ़ाइल स्वरूप का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, पावर प्वाइंट स्लाइड शो, स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint 2007 और इसके बाद के संस्करण का उपयोग करके फ़ाइल बनाई गई है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT एक्सटेंशन वाली एक फ़ाइल PowerPoint फ़ाइल का प्रतिनिधित्व करती है जिसमें स्लाइड शो के रूप में प्रदर्शित करने के लिए स्लाइड का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उच्चतर संस्करणों के साथ बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX एक्सटेंशन वाली फाइलें लोकप्रिय Microsoft PowerPoint एप्लिकेशन के साथ बनाई गई प्रस्तुति फाइलें हैं। प्रस्तुति फ़ाइल प्रारूप पीपीटी के पिछले संस्करण के विपरीत जो बाइनरी था, पीपीटीएक्स प्रारूप माइक्रोसॉफ्ट पावरपॉइंट ओपन एक्सएमएल प्रस्तुति फ़ाइल प्रारूप पर आधारित है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pptx) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
