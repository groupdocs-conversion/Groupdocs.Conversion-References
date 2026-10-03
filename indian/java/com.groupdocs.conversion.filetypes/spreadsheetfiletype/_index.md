---
title: "SpreadsheetFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "स्प्रेडशीट दस्तावेज़ों को परिभाषित करता है।"
type: docs
weight: 25
url: /hi/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

स्प्रेडशीट दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
स्प्रेडशीट फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet)।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Xls](#Xls) | XLS Excel बाइनरी फ़ाइल फ़ॉर्मेट को दर्शाता है। |
|
|  | [Xlsx](#Xlsx) | XLSX माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है, जिसे माइक्रोसॉफ्ट ने माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ प्रस्तुत किया था। |
|
|  | [Xlsm](#Xlsm) | XLSM एक प्रकार की स्प्रेडशीट फ़ाइल है जो मैक्रो का समर्थन करती है। |
|
|  | [Xlsb](#Xlsb) | XLSB फ़ाइल फ़ॉर्मेट Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड्स और संरचनाओं का संग्रह है जो Excel वर्कबुक की सामग्री को निर्दिष्ट करता है। |
|
|  | [Ods](#Ods) | ODS एक्सटेंशन वाली फ़ाइलें OpenDocument स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट को दर्शाती हैं, जिन्हें उपयोगकर्ता द्वारा संपादित किया जा सकता है। |
|
|  | [Ots](#Ots) | .ots एक्सटेंशन वाली फ़ाइल एक OpenDocument स्प्रेडशीट टेम्प्लेट फ़ाइल है, जो Apache OpenOffice में शामिल Calc एप्लिकेशन सॉफ़्टवेयर के साथ बनाई जाती है। |
|
|  | [Xltx](#Xltx) | XLTX फ़ाइल Microsoft Excel टेम्प्लेट को दर्शाती है, जो Office OpenXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित है। |
|
|  | [Xlt](#Xlt) | .XLT एक्सटेंशन वाली फ़ाइलें Microsoft Excel के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं, जो एक स्प्रेडशीट एप्लिकेशन है और Microsoft Office सूट का हिस्सा है। |
|
|  | [Xltm](#Xltm) | XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों को दर्शाता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्प्लेट फ़ाइलों के रूप में उत्पन्न की जाती हैं। |
|
|  | [Tsv](#Tsv) | Tab-Separated Values (TSV) फ़ाइल फ़ॉर्मेट टैब द्वारा विभाजित डेटा को साधारण टेक्स्ट फ़ॉर्मेट में दर्शाता है। |
|
|  | [Xlam](#Xlam) | XLAM एक मैक्रो-सक्षम ऐड-इन फ़ाइल है, जिसका उपयोग स्प्रेडशीट में नई फ़ंक्शन जोड़ने के लिए किया जाता है। |
|
|  | [Csv](#Csv) | CSV (Comma Separated Values) एक्सटेंशन वाली फ़ाइलें साधारण टेक्स्ट फ़ाइलें हैं, जिनमें कॉमा द्वारा विभाजित मानों के साथ डेटा रिकॉर्ड होते हैं। |
|
|  | [Fods](#Fods) | .fods एक्सटेंशन वाली फ़ाइल OpenDocument स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट का एक प्रकार है, जो पंक्तियों और स्तंभों में डेटा संग्रहीत करती है। |
|
|  | [Dif](#Dif) | DIF का अर्थ Data Interchange Format है, जो विभिन्न अनुप्रयोगों के बीच स्प्रेडशीट डेटा को आयात/निर्यात करने के लिए उपयोग किया जाता है। |
|
|  | [Sxc](#Sxc) | फ़ाइल फ़ॉर्मेट SXC (Sun XML Calc) OpenOffice.org नामक ऑफिस सूट का हिस्सा है। |
|
|  | [Numbers](#Numbers) | फ़ाइलें जिनका .numbers एक्सटेंशन है, स्प्रेडशीट फ़ाइल प्रकार के रूप में वर्गीकृत हैं, इसलिए वे .xlsx फ़ाइलों के समान हैं; लेकिन Numbers फ़ाइलें Apple iWork Numbers स्प्रेडशीट सॉफ़्टवेयर का उपयोग करके बनाई जाती हैं। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS Excel Binary File Format को दर्शाता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ OpenOffice Calc या Apple Numbers जैसे समान स्प्रेडशीट प्रोग्रामों द्वारा बनाई जा सकती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है, जिसे माइक्रोसॉफ्ट ने माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ प्रस्तुत किया था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM एक प्रकार की स्प्रेडशीट फ़ाइल है जो मैक्रो का समर्थन करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB फ़ाइल फ़ॉर्मेट Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड्स और संरचनाओं का संग्रह है जो Excel वर्कबुक की सामग्री को निर्दिष्ट करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


ODS एक्सटेंशन वाली फ़ाइलें OpenDocument Spreadsheet Document फ़ॉर्मेट को दर्शाती हैं, जिन्हें उपयोगकर्ता संपादित कर सकता है। डेटा ODF फ़ाइल के भीतर पंक्तियों और स्तंभों में संग्रहीत होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


.ots एक्सटेंशन वाली फ़ाइल OpenDocument Spreadsheet Template फ़ाइल है, जो Apache OpenOffice में शामिल Calc एप्लिकेशन सॉफ़्टवेयर से बनाई जाती है। Calc एप्लिकेशन सॉफ़्टवेयर Microsoft Office में उपलब्ध Excel के समान है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


XLTX फ़ाइल Microsoft Excel Template को दर्शाती है, जो Office OpenXML फ़ाइल फ़ॉर्मेट विशिष्टताओं पर आधारित है। इसका उपयोग एक मानक टेम्प्लेट फ़ाइल बनाने के लिए किया जाता है, जिसे XLTX फ़ाइल में निर्दिष्ट समान सेटिंग्स वाले XLSX फ़ाइलों को उत्पन्न करने के लिए उपयोग किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


.XLT एक्सटेंशन वाली फ़ाइलें Microsoft Excel द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जो Microsoft Office सूट का हिस्सा स्प्रेडशीट एप्लिकेशन है। Microsoft Office 97-2003 नई XLT फ़ाइलें बनाने और इन्हें खोलने का समर्थन करता था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों को दर्शाता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्प्लेट फ़ाइलों के रूप में उत्पन्न की जाती हैं। XLTM फ़ाइलें संरचना में XLTX के समान हैं, सिवाय इसके कि बाद वाला मैक्रो के साथ टेम्प्लेट फ़ाइलें बनाने का समर्थन नहीं करता।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Tab-Separated Values (TSV) फ़ाइल फ़ॉर्मेट टैब द्वारा विभाजित डेटा को साधारण टेक्स्ट फ़ॉर्मेट में दर्शाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM एक Macro-Enabled Add-In फ़ाइल है, जिसका उपयोग स्प्रेडशीट में नई फ़ंक्शन जोड़ने के लिए किया जाता है। Add-In एक अतिरिक्त प्रोग्राम है जो अतिरिक्त कोड चलाता है और स्प्रेडशीट के लिए अतिरिक्त कार्यक्षमता प्रदान करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


CSV (Comma Separated Values) एक्सटेंशन वाली फ़ाइलें साधारण टेक्स्ट फ़ाइलें हैं, जिनमें कॉमा द्वारा विभाजित मानों के साथ डेटा रिकॉर्ड होते हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


.fods एक्सटेंशन वाली फ़ाइल OpenDocument Spreadsheet दस्तावेज़ फ़ॉर्मेट का एक प्रकार है, जो डेटा को पंक्तियों और स्तंभों में संग्रहीत करता है। यह फ़ॉर्मेट OASIS द्वारा प्रकाशित और बनाए रखे गए ODF 1.2 विशिष्टताओं का हिस्सा है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF का अर्थ Data Interchange Format है, जिसका उपयोग विभिन्न अनुप्रयोगों के बीच स्प्रेडशीट डेटा को आयात/निर्यात करने के लिए किया जाता है। इनमें Microsoft Excel, OpenOffice Calc, StarCalc और कई अन्य शामिल हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


फ़ाइल फ़ॉर्मेट SXC (Sun XML Calc) OpenOffice.org नामक ऑफिस सूट से संबंधित है। यह फ़ॉर्मेट उपयोगकर्ताओं की स्प्रेडशीट आवश्यकताओं को पूरा करता है क्योंकि यह XML आधारित स्प्रेडशीट फ़ाइल फ़ॉर्मेट है। SXC फ़ॉर्मेट फ़ॉर्मूले, फ़ंक्शन, मैक्रो और चार्ट के साथ DataPilot को भी समर्थन देता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


.numbers एक्सटेंशन वाली फ़ाइलें स्प्रेडशीट फ़ाइल प्रकार के रूप में वर्गीकृत हैं, इसलिए वे .xlsx फ़ाइलों के समान हैं; लेकिन Numbers फ़ाइलें Apple iWork Numbers स्प्रेडशीट सॉफ़्टवेयर का उपयोग करके बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://docs.fileformat.com/spreadsheet/numbers).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
