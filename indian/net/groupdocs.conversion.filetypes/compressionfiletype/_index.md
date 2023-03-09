---
title: CompressionFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: संपड़न स्वरूपं क परभषत करत है नम्न फ़इल प्रकर शमल हैं Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . संपड़न प्ररूपं के बरे में और जनेंयहँhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /hi/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

संपीड़न स्वरूपों को परिभाषित करता है। निम्न फ़ाइल प्रकार शामिल हैं: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . संपीड़न प्रारूपों के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2, ज्यादातर UNIX या Linux सिस्टम पर BZIP2 ओपन सोर्स कंप्रेशन विधि का उपयोग करके उत्पन्न की गई संपीड़ित फ़ाइलें हैं। यह एक फ़ाइल के संपीड़न के लिए प्रयोग किया जाता है और यह एकाधिक फ़ाइलों के संग्रह के लिए नहीं है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab एक्सटेंशन वाली फ़ाइल एक विंडोज़ कैबिनेट फ़ाइल से संबंधित है जो सिस्टम फ़ाइलों की श्रेणी से संबंधित है। यह एक फ़ाइल है जो Microsoft Windows के संस्करणों में संग्रह फ़ाइल स्वरूप में सहेजी गई है जो LZX, क्वांटम और ZIP जैसे संपीड़ित डेटा एल्गोरिदम का समर्थन करती है. इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio एक सामान्य फाइल आर्काइवर यूटिलिटी और इससे जुड़ा फाइल फॉर्मेट है। यह मुख्य रूप से यूनिक्स जैसे कंप्यूटर ऑपरेटिंग सिस्टम पर स्थापित है। |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | एक GZ फ़ाइल एक संपीड़ित संग्रह है जिसे मानक gzip (GNU ज़िप) संपीड़न एल्गोरिथम का उपयोग करके बनाया गया है। इसमें कई संपीड़ित फ़ाइलें, निर्देशिकाएं और फ़ाइल स्टब्स हो सकते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip फ़ाइल एक कंप्रेस्ड आर्काइव है जिसे मानक gzip (GNU zip) कम्प्रेशन एल्गोरिथम का उपयोग करके बनाया गया है। इसमें कई संपीड़ित फ़ाइलें, निर्देशिकाएं और फ़ाइल स्टब्स हो सकते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz एक्सटेंशन वाली फाइल Lzip के साथ बनाई गई एक कंप्रेस्ड आर्काइव फाइल है, जो कम्प्रेशन के लिए एक फ्री कमांड-लाइन टूल है। यह समर्थन फ़ाइलों को संपीड़ित करने के लिए संयोजन का समर्थन करता है। LZ फाइलें मीडिया प्रकार की एप्लिकेशन/lzip होती हैं और BZ2. की तुलना में उच्च संपीड़न अनुपात का समर्थन करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma एक्सटेंशन वाली फ़ाइल LZMA (लेम्पेल-ज़िव-मार्कोव चेन एल्गोरिथम) संपीड़न विधि का उपयोग करके बनाई गई एक संपीड़ित संग्रह फ़ाइल है। ये मुख्य रूप से यूनिक्स ऑपरेटिंग सिस्टम पर पाए जाते हैं/उपयोग किए जाते हैं और फ़ाइल आकार को कम करने के लिए ज़िप जैसे अन्य संपीड़न एल्गोरिदम के समान होते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar एक्सटेंशन वाली फाइलें आर्काइव फाइलें होती हैं जो सूचनाओं को कंप्रेस्ड या नॉर्मल फॉर्म में स्टोर करने के लिए बनाई जाती हैं। RAR, जो रोशल आर्काइव फ़ाइल स्वरूप के लिए खड़ा है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z उच्च संपीड़न अनुपात वाली फ़ाइलों और फ़ोल्डरों को संपीड़ित करने के लिए एक संग्रह प्रारूप है। यह ओपन सोर्स आर्किटेक्चर पर आधारित है जो किसी भी संपीड़न और एन्क्रिप्शन एल्गोरिदम का उपयोग करना संभव बनाता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar एक्सटेंशन वाली फ़ाइलें एक या अधिक फ़ाइलों को एकत्रित करने के लिए यूनिक्स-आधारित उपयोगिता के साथ बनाए गए संग्रह हैं। संग्रह में फ़ाइलों के साथ-साथ फ़ोल्डरों को जोड़ने के समर्थन के साथ एक से अधिक फ़ाइलों को एक असम्पीडित प्रारूप में संग्रहीत किया जाता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ एक कंप्रेस्ड फ़ाइल फ़ॉर्मैट है जो LZMA2 कम्प्रेशन एल्गोरिथम का उपयोग करता है। इसे लोकप्रिय gzip और bzip2 स्वरूपों के प्रतिस्थापन के रूप में डिज़ाइन किया गया था, और इन पुराने मानकों पर कई लाभ प्रदान करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ फ़ाइल UNIX संपीड़ित डेटा फ़ाइलों से संबंधित फ़ाइलों की एक श्रेणी है। संपीड़ित यूनिक्स फ़ाइलें Z फ़ाइल का सबसे लोकप्रिय और व्यापक रूप से उपयोग किया जाने वाला एक्सटेंशन प्रकार हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip एक्सटेंशन वाली फ़ाइल एक संग्रह है जिसमें एक या अधिक फ़ाइलें या निर्देशिकाएं हो सकती हैं। ज़िप फ़ाइल आकार को कम करने के लिए संग्रह में सम्मिलित फ़ाइलों पर संपीड़न लागू किया जा सकता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/compression/zip/) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
