---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "प्रेजेंटेशन फ़ाइल फ़ॉर्मेट को परिभाषित करता है जो रिकॉर्ड्स के संग्रह को संग्रहीत करता है ताकि स्लाइड, आकार, टेक्स्ट, एनीमेशन, वीडियो, ऑडियो और एम्बेडेड ऑब्जेक्ट्स जैसे प्रेजेंटेशन डेटा को समायोजित किया जा सके। निम्नलिखित फ़ाइल प्रकार शामिल हैं Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx। प्रेजेंटेशन फ़ॉर्मेट के बारे में अधिक जानने के लिए यहाँ देखें https//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /hi/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

प्रेजेंटेशन फ़ाइल फ़ॉर्मेट को परिभाषित करता है जो रिकॉर्ड्स के संग्रह को संग्रहीत करता है ताकि स्लाइड, आकार, टेक्स्ट, एनीमेशन, वीडियो, ऑडियो और एम्बेडेड ऑब्जेक्ट्स जैसे प्रेजेंटेशन डेटा को समायोजित किया जा सके। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). प्रेजेंटेशन फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation) देखें।

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | FODP एक्सटेंशन वाली फ़ाइलें OpenDocument फ्लैट XML प्रेजेंटेशन को दर्शाती हैं। प्रेजेंटेशन फ़ाइल OpenDocument फ़ॉर्मेट में सहेजी जाती है, लेकिन मानक .ODP फ़ाइलों द्वारा उपयोग किए जाने वाले .ZIP कंटेनर के बजाय फ्लैट XML फ़ॉर्मेट का उपयोग करके सहेजी जाती है। |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP एक्सटेंशन वाली फ़ाइलें OASISOpen मानक में OpenOffice.org द्वारा उपयोग किए जाने वाले प्रेजेंटेशन फ़ाइल फ़ॉर्मेट को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/odp) देखें। |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | .OTP एक्सटेंशन वाली फ़ाइलें OASIS OpenDocument मानक फ़ॉर्मेट में एप्लिकेशन द्वारा बनाई गई प्रेजेंटेशन टेम्प्लेट फ़ाइलें दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/otp) देखें। |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | .POT एक्सटेंशन वाली फ़ाइलें PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्प्लेट फ़ाइलें दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pot) देखें। |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | POTM एक्सटेंशन वाली फ़ाइलें मैक्रो समर्थन वाली Microsoft PowerPoint टेम्प्लेट फ़ाइलें हैं। POTM फ़ाइलें PowerPoint 2007 या उससे ऊपर के संस्करणों से बनाई जाती हैं और डिफ़ॉल्ट सेटिंग्स शामिल करती हैं जिन्हें आगे की प्रेजेंटेशन फ़ाइलें बनाने के लिए उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/potm) देखें। |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | .POTX एक्सटेंशन वाली फ़ाइलें Microsoft PowerPoint 2007 और उससे ऊपर के संस्करणों से बनाई गई Microsoft PowerPoint टेम्प्लेट प्रेजेंटेशन को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/potx) देखें। |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint स्लाइड शो, फ़ाइलें स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाई जाती हैं। PPS फ़ाइलों को पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pps) देखें। |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम स्लाइड शो फ़ाइल फ़ॉर्मेट को दर्शाती हैं जो Microsoft PowerPoint 2007 या उससे उच्च संस्करण से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/ppsm) देखें। |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, PowerPoint स्लाइड शो, फ़ाइलें Microsoft PowerPoint 2007 और उससे ऊपर के संस्करणों का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/ppsx) देखें। |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT एक्सटेंशन वाली फ़ाइल PowerPoint फ़ाइल को दर्शाती है जिसमें स्लाइडशो के रूप में प्रदर्शित करने के लिए स्लाइड्स का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/ppt) देखें। |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम प्रेजेंटेशन फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pptm) देखें। |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX एक्सटेंशन वाली फ़ाइलें लोकप्रिय Microsoft PowerPoint एप्लिकेशन द्वारा बनाई गई प्रस्तुति फ़ाइलें हैं। पिछले संस्करण PPT जो बाइनरी था, के विपरीत, PPTX फ़ॉर्मेट Microsoft PowerPoint ओपन XML प्रस्तुति फ़ाइल फ़ॉर्मेट पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pptx) देखें। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
