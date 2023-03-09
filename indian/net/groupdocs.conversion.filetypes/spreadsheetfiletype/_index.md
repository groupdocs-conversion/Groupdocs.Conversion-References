---
title: SpreadsheetFileType
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: स्प्रेडशट दस्तवेज़ं क परभषत करत है नम्न फ़इल प्रकर शमल हैं Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . स्प्रेडशट प्ररूपं के बरे में अधक जनेंयहँhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /hi/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

स्प्रेडशीट दस्तावेज़ों को परिभाषित करता है। निम्न फ़ाइल प्रकार शामिल हैं: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . स्प्रेडशीट प्रारूपों के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | सीरियलाइज़ेशन कंस्ट्रक्टर |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV (कॉमा सेपरेटेड वैल्यूज़) एक्सटेंशन वाली फ़ाइलें सादा पाठ फ़ाइलों का प्रतिनिधित्व करती हैं जिनमें अल्पविराम से अलग किए गए मानों वाले डेटा के रिकॉर्ड होते हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF डेटा इंटरचेंज फ़ॉर्मेट के लिए है जिसका उपयोग विभिन्न अनुप्रयोगों के बीच स्प्रेडशीट डेटा आयात/निर्यात करने के लिए किया जाता है। इनमें माइक्रोसॉफ्ट एक्सेल, ओपनऑफिस कैल्क, स्टारकैल्क और कई अन्य शामिल हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | .fods एक्सटेंशन वाली फ़ाइल एक प्रकार का OpenDocument स्प्रेडशीट दस्तावेज़ प्रारूप है जो पंक्तियों और स्तंभों में डेटा संग्रहीत करता है। प्रारूप OASIS द्वारा प्रकाशित और अनुरक्षित ODF 1.2 विनिर्देशों के हिस्से के रूप में निर्दिष्ट किया गया है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers एक्सटेंशन वाली फ़ाइलें स्प्रेडशीट फ़ाइल प्रकार के रूप में वर्गीकृत की जाती हैं, इसलिए वे .xlsx फ़ाइलों के समान होती हैं; लेकिन Numbers फ़ाइलें Apple iWork Numbers स्प्रेडशीट सॉफ़्टवेयर का उपयोग करके बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS एक्सटेंशन वाली फ़ाइलें OpenDocument स्प्रेडशीट दस्तावेज़ प्रारूप के लिए होती हैं जो उपयोगकर्ता द्वारा संपादन योग्य होती हैं। डेटा को ODF फ़ाइल में पंक्तियों और स्तंभों में संग्रहीत किया जाता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | .ots एक्सटेंशन वाली फ़ाइल एक OpenDocument स्प्रेडशीट टेम्प्लेट फ़ाइल है जिसे Apache OpenOffice में शामिल Calc एप्लिकेशन सॉफ़्टवेयर के साथ बनाया गया है। कैल्क एप्लीकेशन सॉफ्टवेयर माइक्रोसॉफ्ट ऑफिस में उपलब्ध एक्सेल के समान है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | फ़ाइल प्रारूप SXC (Sun XML Calc) OpenOffice.org नामक एक कार्यालय सुइट से संबंधित है। यह प्रारूप आम तौर पर उपयोगकर्ताओं की स्प्रैडशीट आवश्यकताओं से संबंधित है क्योंकि यह एक XML आधारित स्प्रैडशीट फ़ाइल स्वरूप है। SXC प्रारूप DataPilot के साथ-साथ सूत्रों, कार्यों, मैक्रोज़ और चार्ट का समर्थन करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | एक टैब-पृथक मान (TSV) फ़ाइल स्वरूप सादे पाठ प्रारूप में टैब के साथ अलग किए गए डेटा का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM एक मैक्रो-सक्षम ऐड-इन फ़ाइल है जिसका उपयोग स्प्रेडशीट में नए फ़ंक्शन जोड़ने के लिए किया जाता है। ऐड-इन एक पूरक प्रोग्राम है जो अतिरिक्त कोड चलाता है और स्प्रेडशीट के लिए अतिरिक्त कार्यक्षमता प्रदान करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS एक्सेल बाइनरी फ़ाइल स्वरूप का प्रतिनिधित्व करता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा बनाई जा सकती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB फाइल फॉर्मेट एक्सेल बाइनरी फाइल फॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड्स और स्ट्रक्चर्स का एक संग्रह है जो एक्सेल वर्कबुक कंटेंट को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM एक प्रकार की स्प्रेडशीट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX Microsoft Excel दस्तावेज़ों के लिए प्रसिद्ध प्रारूप है जिसे Microsoft द्वारा Microsoft Office 2007 की रिलीज़ के साथ पेश किया गया था। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | .XLT एक्सटेंशन वाली फाइलें माइक्रोसॉफ्ट एक्सेल के साथ बनाई गई टेम्प्लेट फाइलें हैं जो एक स्प्रेडशीट एप्लिकेशन है जो माइक्रोसॉफ्ट ऑफिस सूट के हिस्से के रूप में आती है। Microsoft Office 97-2003 ने नई XLT फ़ाइलों को बनाने के साथ-साथ इन्हें खोलने का भी समर्थन किया। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों का प्रतिनिधित्व करता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न होती हैं। XLTM फाइलें संरचना में XLTX के समान हैं, इसके अलावा बाद में मैक्रोज़ के साथ टेम्पलेट फ़ाइलों को बनाने का समर्थन नहीं करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX फ़ाइल Microsoft Excel टेम्पलेट का प्रतिनिधित्व करती है जो कि Office OpenXML फ़ाइल प्रारूप विनिर्देशों पर आधारित है। इसका उपयोग एक मानक टेम्पलेट फ़ाइल बनाने के लिए किया जाता है जिसका उपयोग XLTX फ़ाइल बनाने के लिए किया जा सकता है जो XLTX फ़ाइल में निर्दिष्ट सेटिंग्स को प्रदर्शित करती है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltx) . |

### यह सभी देखें

* class [FileType](../filetype)
* नाम स्थान [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
