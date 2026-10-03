---
title: "EmailFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ईमेल फ़ाइल फ़ॉर्मेट को परिभाषित करता है जो ईमेल एप्लिकेशन द्वारा उनके विभिन्न डेटा जैसे ईमेल संदेश, अटैचमेंट, फ़ोल्डर, पता पुस्तिकाएँ आदि को संग्रहीत करने के लिए उपयोग किए जाते हैं।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

ईमेल फ़ाइल फ़ॉर्मेट को परिभाषित करता है जो ईमेल अनुप्रयोगों द्वारा विभिन्न डेटा जैसे ईमेल संदेश, अटैचमेंट, फ़ोल्डर, पता पुस्तिकाएँ आदि को संग्रहीत करने के लिए उपयोग होते हैं।
निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
ईमेल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Msg](#Msg) | MSG एक फ़ाइल फ़ॉर्मेट है जो Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाता है। |
|
|  | [Eml](#Eml) | EML फ़ाइल फ़ॉर्मेट Outlook और अन्य संबंधित एप्लिकेशन द्वारा सहेजे गए ईमेल संदेशों को दर्शाता है। |
|
|  | [Emlx](#Emlx) | EMLX फ़ाइल फ़ॉर्मेट Apple द्वारा लागू और विकसित किया गया है। |
|
|  | [Vcf](#Vcf) | VCF (वर्चुअल कार्ड फ़ॉर्मेट) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। |
|
|  | [Mbox](#Mbox) | MBox फ़ाइल फ़ॉर्मेट एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए कंटेनर को दर्शाता है। |
|
|  | [Pst](#Pst) | .PST एक्सटेंशन वाली फ़ाइलें Outlook Personal Storage Files (जिसे Personal Storage Table भी कहा जाता है) को दर्शाती हैं जो उपयोगकर्ता की विभिन्न जानकारी संग्रहीत करती हैं। |
|
|  | [Ost](#Ost) | OST या Offline Storage Files उपयोगकर्ता के मेलबॉक्स डेटा को स्थानीय मशीन पर ऑफ़लाइन मोड में, Microsoft Outlook के माध्यम से Exchange Server में पंजीकरण के बाद दर्शाती हैं। |
|
|  | [Olm](#Olm) | .olm एक्सटेंशन वाली फ़ाइल Microsoft Outlook की Mac ऑपरेटिंग सिस्टम के लिए फ़ाइल है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG एक फ़ाइल फ़ॉर्मेट है जो Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML फ़ाइल फ़ॉर्मेट Outlook और अन्य संबंधित अनुप्रयोगों द्वारा सहेजे गए ईमेल संदेशों को दर्शाता है। लगभग सभी ईमेल क्लाइंट इस फ़ॉर्मेट को RFC-822 इंटरनेट संदेश फ़ॉर्मेट मानक के अनुपालन के कारण समर्थन करते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


EMLX फ़ाइल फ़ॉर्मेट Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा आदान‑प्रदान के लिए व्यापक रूप से उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox फ़ाइल फ़ॉर्मेट एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए कंटेनर को दर्शाता है। संदेशों को उनके अटैचमेंट्स के साथ कंटेनर के भीतर संग्रहीत किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


.PST एक्सटेंशन वाली फ़ाइलें Outlook Personal Storage Files (जिसे Personal Storage Table भी कहा जाता है) को दर्शाती हैं जो उपयोगकर्ता की विभिन्न जानकारी संग्रहीत करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST या Offline Storage Files उपयोगकर्ता के मेलबॉक्स डेटा को स्थानीय मशीन पर ऑफ़लाइन मोड में, Microsoft Outlook के माध्यम से Exchange Server में पंजीकरण के बाद दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


.olm एक्सटेंशन वाली फ़ाइल Microsoft Outlook की Mac ऑपरेटिंग सिस्टम के लिए फ़ाइल है। OLM फ़ाइल ईमेल संदेश, जर्नल, कैलेंडर डेटा और अन्य प्रकार के एप्लिकेशन डेटा को संग्रहीत करती है। ये Windows ऑपरेटिंग सिस्टम पर Outlook द्वारा उपयोग की जाने वाली PST फ़ाइलों के समान हैं। हालांकि, Outlook for Mac द्वारा बनाई गई OLM फ़ाइलें Outlook for Windows में नहीं खोली जा सकती\\u2019। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
