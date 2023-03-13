---
title: EmailFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: ईमेल फ़इल स्वरूपं क परभषत करत है जनक उपयग ईमेल अनुप्रयगं द्वर ईमेल संदेशं अनुलग्नकं फ़ल्डरं पत पुस्तकओं आद सहत उनके वभन्न डेट क संग्रहत करने के लए कय जत है में नम्न फ़इल प्रकर शमल हैं Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . ईमेल प्ररूपं के बरे में अधक जनेंयहँhttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /hi/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

ईमेल फ़ाइल स्वरूपों को परिभाषित करता है जिनका उपयोग ईमेल अनुप्रयोगों द्वारा ईमेल संदेशों, अनुलग्नकों, फ़ोल्डरों, पता पुस्तिकाओं आदि सहित उनके विभिन्न डेटा को संग्रहीत करने के लिए किया जाता है। में निम्न फ़ाइल प्रकार शामिल हैं: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . ईमेल प्रारूपों के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EmailFileType](emailfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | ईएमएल फ़ाइल प्रारूप आउटलुक और अन्य प्रासंगिक अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों का प्रतिनिधित्व करता है। लगभग सभी ईमेल करने वाले क्लाइंट RFC-822 इंटरनेट संदेश प्रारूप मानक के अनुपालन के लिए इस फ़ाइल प्रारूप का समर्थन करते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX फ़ाइल स्वरूप Apple द्वारा कार्यान्वित और विकसित किया गया है। Apple मेल एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल स्वरूप का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox फ़ाइल स्वरूप एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए एक कंटेनर का प्रतिनिधित्व करता है। संदेशों को उनके अनुलग्नकों के साथ कंटेनर में संग्रहीत किया जाता है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG एक फ़ाइल स्वरूप है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेशों, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST या ऑफलाइन संग्रहण फ़ाइलें Microsoft Outlook का उपयोग करके एक्सचेंज सर्वर के साथ पंजीकरण पर स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा का प्रतिनिधित्व करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | .PST एक्सटेंशन वाली फाइलें आउटलुक पर्सनल स्टोरेज फाइल्स (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) का प्रतिनिधित्व करती हैं, जो विभिन्न प्रकार की उपयोगकर्ता सूचनाओं को स्टोर करती हैं। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (वर्चुअल कार्ड फॉर्मेट) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल स्वरूप है। लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा विनिमय के लिए प्रारूप का व्यापक रूप से उपयोग किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/vcf) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
