---
title: "EmailFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "ईमेल फ़ाइल फ़ॉर्मेट को परिभाषित करता है जो ईमेल एप्लिकेशन द्वारा उनके विभिन्न डेटा जैसे ईमेल संदेश, अटैचमेंट, फ़ोल्डर, एड्रेस बुक आदि को संग्रहीत करने के लिए उपयोग होते हैं। निम्नलिखित फ़ाइल प्रकार शामिल हैं Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. ईमेल फ़ॉर्मेट के बारे में अधिक जानें यहाँhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /hi/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

ईमेल फ़ाइल फ़ॉर्मेट को परिभाषित करता है जो ईमेल अनुप्रयोगों द्वारा उनके विभिन्न डेटा जैसे ईमेल संदेश, अटैचमेंट, फ़ोल्डर, पता पुस्तिकाएँ आदि को संग्रहीत करने के लिए उपयोग किए जाते हैं। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). ईमेल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email) देखें।

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML फ़ाइल फ़ॉर्मेट उन ईमेल संदेशों को दर्शाता है जो Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे जाते हैं। लगभग सभी ईमेल क्लाइंट इस फ़ॉर्मेट को RFC-822 इंटरनेट संदेश फ़ॉर्मेट मानक के अनुपालन के कारण समर्थन करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/eml) देखें। |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX फ़ाइल फ़ॉर्मेट Apple द्वारा लागू और विकसित किया गया है। Apple Mail अनुप्रयोग ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/emlx) देखें। |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | ICS (iCalendar) फ़ाइल फ़ॉर्मेट का उपयोग कैलेंडरिंग और शेड्यूलिंग जानकारी जैसे इवेंट, टु-डू, और फ्री/बिजी डेटा को दर्शाने और आदान-प्रदान करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/ics) देखें। |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox फ़ाइल फ़ॉर्मेट एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए कंटेनर को दर्शाता है। संदेश अपने अटैचमेंट के साथ कंटेनर के भीतर संग्रहीत होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/email/mbox/) देखें। |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG वह फ़ाइल फ़ॉर्मेट है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्ति या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/msg) देखें। |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | .olm एक्सटेंशन वाली फ़ाइल Microsoft Outlook की मैक ऑपरेटिंग सिस्टम के लिए फ़ाइल है। OLM फ़ाइल ईमेल संदेश, जर्नल, कैलेंडर डेटा और अन्य प्रकार के एप्लिकेशन डेटा को संग्रहीत करती है। ये Windows ऑपरेटिंग सिस्टम पर Outlook द्वारा उपयोग किए जाने वाले PST फ़ाइलों के समान हैं। हालांकि, मैक के लिए Outlook द्वारा बनाई गई OLM फ़ाइलें Windows के लिए Outlook में नहीं खोली जा सकतीं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/olm) देखें। |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST या ऑफ़लाइन स्टोरेज फ़ाइलें Microsoft Outlook का उपयोग करके Exchange सर्वर में पंजीकरण के बाद स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/ost) देखें। |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | .PST एक्सटेंशन वाली फ़ाइलें Outlook पर्सनल स्टोरेज फ़ाइलें (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) को दर्शाती हैं जो विभिन्न उपयोगकर्ता जानकारी को संग्रहीत करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/pst) देखें। |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (वर्चुअल कार्ड फ़ॉर्मेट) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा आदान-प्रदान के लिए व्यापक रूप से उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/vcf) देखें। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
