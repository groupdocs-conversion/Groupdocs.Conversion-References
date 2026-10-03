---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "स्प्रेडशीट दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx। स्प्रेडशीट फ़ॉर्मेट्स के बारे में अधिक जानने के लिए यहाँ https//wiki.fileformat.com/spreadsheet देखें।"
type: docs
weight: 1240
url: /hi/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

स्प्रेडशीट दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). स्प्रेडशीट फ़ॉर्मेट्स के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet) देखें।

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV (कॉमा सेपरेटेड वैल्यूज़) एक्सटेंशन वाली फ़ाइलें साधारण टेक्स्ट फ़ाइलें होती हैं जिनमें कॉमा से अलग किए गए मानों के साथ डेटा रिकॉर्ड होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/csv) देखें। |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF का अर्थ Data Interchange Format है, जो विभिन्न अनुप्रयोगों के बीच स्प्रेडशीट डेटा को आयात/निर्यात करने के लिए उपयोग किया जाता है। इनमें Microsoft Excel, OpenOffice Calc, StarCalc और कई अन्य शामिल हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/dif) देखें। |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel एक Office Open XML SpreadsheetML है जो ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल में संग्रहीत होता है। |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | .fods एक्सटेंशन वाली फ़ाइल OpenDocument Spreadsheet दस्तावेज़ फ़ॉर्मेट का एक प्रकार है जो डेटा को पंक्तियों और स्तंभों में संग्रहीत करता है। यह फ़ॉर्मेट OASIS द्वारा प्रकाशित और बनाए रखे गए ODF 1.2 विनिर्देशों का हिस्सा है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/fods) देखें। |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers एक्सटेंशन वाली फ़ाइलें स्प्रेडशीट फ़ाइल प्रकार के रूप में वर्गीकृत हैं, इसलिए वे .xlsx फ़ाइलों के समान हैं; लेकिन Numbers फ़ाइलें Apple iWork Numbers स्प्रेडशीट सॉफ़्टवेयर का उपयोग करके बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/numbers) देखें। |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS एक्सटेंशन वाली फ़ाइलें OpenDocument Spreadsheet दस्तावेज़ फ़ॉर्मेट को दर्शाती हैं जिन्हें उपयोगकर्ता संपादित कर सकता है। डेटा ODF फ़ाइल के भीतर पंक्तियों और स्तंभों में संग्रहीत होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/ods) देखें। |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | .ots एक्सटेंशन वाली फ़ाइल एक OpenDocument Spreadsheet टेम्प्लेट फ़ाइल है जो Apache OpenOffice में शामिल Calc एप्लिकेशन सॉफ़्टवेयर द्वारा बनाई जाती है। Calc एप्लिकेशन सॉफ़्टवेयर Microsoft Office में उपलब्ध Excel के समान है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/ots) देखें। |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | फ़ाइल फ़ॉर्मेट SXC (Sun XML Calc) OpenOffice.org नामक ऑफिस सूट से संबंधित है। यह फ़ॉर्मेट उपयोगकर्ताओं की स्प्रेडशीट आवश्यकताओं को पूरा करता है क्योंकि यह एक XML आधारित स्प्रेडशीट फ़ाइल फ़ॉर्मेट है। SXC फ़ॉर्मेट फ़ॉर्मूले, फ़ंक्शन, मैक्रो और चार्ट के साथ DataPilot को भी समर्थन देता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/spreadsheet/sxc) देखें। |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | एक टैब-सेपरेटेड वैल्यूज़ (TSV) फ़ाइल फ़ॉर्मेट टैब द्वारा अलग किए गए डेटा को सादे टेक्स्ट फ़ॉर्मेट में दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/tsv)। |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM एक मैक्रो-एनेबल्ड ऐड-इन फ़ाइल है जो स्प्रेडशीट में नई फ़ंक्शन जोड़ने के लिए उपयोग की जाती है। एक ऐड-इन एक अतिरिक्त प्रोग्राम है जो अतिरिक्त कोड चलाता है और स्प्रेडशीट के लिए अतिरिक्त कार्यक्षमता प्रदान करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/spreadsheet/xlam/)। |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS एक्सेल बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। ऐसी फ़ाइलें माइक्रोसॉफ्ट एक्सेल तथा ओपनऑफ़िस कैलक या एप्पल नंबर जैसे समान स्प्रेडशीट प्रोग्रामों द्वारा बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xls)। |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB फ़ाइल फ़ॉर्मेट एक्सेल बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड्स और संरचनाओं का संग्रह है जो एक्सेल वर्कबुक सामग्री को परिभाषित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xlsb)। |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM मैक्रो को सपोर्ट करने वाले स्प्रेडशीट फ़ाइलों का एक प्रकार है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xlsm)। |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे माइक्रोसॉफ्ट ने माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ पेश किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xlsx)। |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | .XLT एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट एक्सेल द्वारा बनाई गई टेम्पलेट फ़ाइलें हैं, जो माइक्रोसॉफ्ट ऑफिस सूट का हिस्सा स्प्रेडशीट एप्लिकेशन है। माइक्रोसॉफ्ट ऑफिस 97-2003 ने नई XLT फ़ाइलें बनाने और इन्हें खोलने का समर्थन किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xlt)। |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों को दर्शाता है जो माइक्रोसॉफ्ट एक्सेल द्वारा मैक्रो-एनेबल्ड टेम्पलेट फ़ाइलों के रूप में उत्पन्न की जाती हैं। XLTM फ़ाइलें संरचना में XLTX के समान हैं, सिवाय इसके कि बाद वाली मैक्रो के साथ टेम्पलेट फ़ाइलें बनाने का समर्थन नहीं करती। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xltm)। |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX फ़ाइल माइक्रोसॉफ्ट एक्सेल टेम्पलेट को दर्शाती है जो ऑफिस ओपनXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित है। इसका उपयोग एक मानक टेम्पलेट फ़ाइल बनाने के लिए किया जाता है जिसे XLTX फ़ाइल में निर्दिष्ट समान सेटिंग्स के साथ XLSX फ़ाइलें उत्पन्न करने के लिए उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/spreadsheet/xltx)। |

### देखें भी

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
