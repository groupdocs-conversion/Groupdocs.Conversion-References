---
title: "DiagramFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "डायग्राम दस्तावेज़ को परिभाषित करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

डायग्राम दस्तावेज़ को परिभाषित करता है। निम्नलिखित प्रकार शामिल हैं:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Vsd](#Vsd) | VSD फ़ाइलें Microsoft Visio एप्लिकेशन के साथ बनाई गई ड्रॉइंग्स हैं जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके बीच के कनेक्शन को दर्शाती हैं। |
|
|  | [Vsdx](#Vsdx) | .VSDX एक्सटेंशन वाली फ़ाइलें Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाती हैं, जो Microsoft Office 2013 से आगे प्रस्तुत किया गया है। |
|
|  | [Vss](#Vss) | VSS Microsoft Visio 2007 और उससे पहले के संस्करणों के साथ बनाई गई स्टेंसिल फ़ाइलें हैं। |
|
|  | [Vst](#Vst) | VST एक्सटेंशन वाली फ़ाइलें Microsoft Visio के साथ बनाई गई वेक्टर इमेज फ़ाइलें हैं और आगे की फ़ाइलें बनाने के लिए टेम्प्लेट के रूप में कार्य करती हैं। |
|
|  | [Vsx](#Vsx) | .VSX एक्सटेंशन वाली फ़ाइलें उन स्टेंसिल्स को दर्शाती हैं जिनमें ड्रॉइंग्स और आकार होते हैं, जो Microsoft Visio में डायग्राम बनाने के लिए उपयोग किए जाते हैं। |
|
|  | [Vtx](#Vtx) | VTX एक्सटेंशन वाली फ़ाइल एक Microsoft Visio ड्रॉइंग टेम्प्लेट है जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजी जाती है। |
|
|  | [Vdw](#Vdw) | VDW Visio ग्राफ़िक्स सर्विस फ़ाइल फ़ॉर्मेट है जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम्स और स्टोरेज को निर्दिष्ट करता है। |
|
|  | [Vdx](#Vdx) | Microsoft Visio में बनाई गई कोई भी ड्रॉइंग या चार्ट, लेकिन XML फ़ॉर्मेट में सहेजी गई, .VDX एक्सटेंशन रखती है। |
|
|  | [Vssx](#Vssx) | .VSSX एक्सटेंशन वाली फ़ाइलें Microsoft Visio 2013 और उसके बाद के संस्करणों के साथ बनाई गई ड्रॉइंग स्टेंसिल हैं। |
|
|  | [Vstx](#Vstx) | VSTX एक्सटेंशन वाली फ़ाइलें Microsoft Visio 2013 और उसके बाद के संस्करणों के साथ बनाई गई ड्रॉइंग टेम्प्लेट फ़ाइलें हैं। |
|
|  | [Vsdm](#Vsdm) | VSDM एक्सटेंशन वाली फ़ाइलें Microsoft Visio एप्लिकेशन के साथ बनाई गई ड्रॉइंग फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। |
|
|  | [Vssm](#Vssm) | .VSSM एक्सटेंशन वाली फ़ाइलें Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रोज़ के लिए समर्थन प्रदान करती हैं। |
|
|  | [Vstm](#Vstm) | VSTM एक्सटेंशन वाली फ़ाइलें Microsoft Visio के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD फ़ाइलें Microsoft Visio एप्लिकेशन के साथ बनाई गई ड्रॉइंग्स हैं जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके बीच के कनेक्शन को दर्शाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsd)।


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


.VSDX एक्सटेंशन वाली फ़ाइलें Microsoft Visio फ़ाइल फ़ॉर्मेट को दर्शाती हैं, जो Microsoft Office 2013 से आगे प्रस्तुत किया गया है। इसे बाइनरी फ़ाइल फ़ॉर्मेट .VSD को बदलने के लिए विकसित किया गया था, जो Microsoft Visio के पहले संस्करणों द्वारा समर्थित था।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsdx)।


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS Microsoft Visio 2007 और उससे पहले के संस्करणों के साथ बनाई गई स्टेंसिल फ़ाइलें हैं। स्टेंसिल फ़ाइलें ड्रॉइंग ऑब्जेक्ट्स प्रदान करती हैं जिन्हें .VSD Visio ड्रॉइंग में शामिल किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vss)।


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


VST एक्सटेंशन वाली फ़ाइलें Microsoft Visio के साथ बनाई गई वेक्टर इमेज फ़ाइलें हैं और आगे की फ़ाइलें बनाने के लिए टेम्प्लेट के रूप में कार्य करती हैं। ये टेम्प्लेट फ़ाइलें बाइनरी फ़ाइल फ़ॉर्मेट में होती हैं और डिफ़ॉल्ट लेआउट और सेटिंग्स को शामिल करती हैं जो नई Visio ड्रॉइंग्स के निर्माण में उपयोग की जाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vst)।


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


.VSX एक्सटेंशन वाली फ़ाइलें उन स्टेंसिल्स को दर्शाती हैं जिनमें ड्रॉइंग्स और आकार होते हैं, जो Microsoft Visio में डायग्राम बनाने के लिए उपयोग किए जाते हैं। VSX फ़ाइलें XML फ़ाइल फ़ॉर्मेट में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsx)।


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


VTX एक्सटेंशन वाली फ़ाइल एक Microsoft Visio ड्रॉइंग टेम्प्लेट है जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजी जाती है। यह टेम्प्लेट मूल सेटिंग्स वाली फ़ाइल प्रदान करने के लिए बनाया गया है, जिसका उपयोग समान सेटिंग्स वाली कई Visio फ़ाइलें बनाने में किया जा सकता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vtx)।


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW Visio ग्राफ़िक्स सर्विस फ़ाइल फ़ॉर्मेट है जो वेब ड्रॉइंग को रेंडर करने के लिए आवश्यक स्ट्रीम्स और स्टोरेज को निर्दिष्ट करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Microsoft Visio में बनाया गया कोई भी चित्र या चार्ट, लेकिन XML फ़ॉर्मेट में सहेजा गया हो, .VDX एक्सटेंशन रखता है। Visio सॉफ़्टवेयर, जो Microsoft द्वारा विकसित किया गया है, में Visio ड्रॉइंग XML फ़ाइल बनाई जाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


`.VSSX` एक्सटेंशन वाली फ़ाइलें Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग स्टेंसिल हैं। VSSX फ़ाइल फ़ॉर्मेट को Visio 2013 और उसके बाद के संस्करणों में खोला जा सकता है। Visio फ़ाइलें विभिन्न ड्रॉइंग तत्वों जैसे आकारों का संग्रह, कनेक्टर, फ्लोचार्ट, नेटवर्क लेआउट, UML डायग्राम आदि के प्रतिनिधित्व के लिए जानी जाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


VSTX एक्सटेंशन वाली फ़ाइलें Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई ड्रॉइंग टेम्प्लेट फ़ाइलें हैं। ये VSTX फ़ाइलें Visio ड्रॉइंग बनाने के लिए प्रारंभिक बिंदु प्रदान करती हैं, जिन्हें .VSDX फ़ाइलों के रूप में सहेजा जाता है, और इनमें डिफ़ॉल्ट लेआउट और सेटिंग्स होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


VSDM एक्सटेंशन वाली फ़ाइलें Microsoft Visio एप्लिकेशन से बनाई गई ड्रॉइंग फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDM फ़ाइलें OPC/XML ड्रॉइंग हैं जो VSDX के समान हैं, लेकिन फ़ाइल खोलने पर मैक्रो चलाने की क्षमता भी प्रदान करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


.VSSM एक्सटेंशन वाली फ़ाइलें Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। एक VSSM फ़ाइल को खोलने पर मैक्रो चलाने की अनुमति देती है जिससे डायग्राम में आकारों का वांछित फ़ॉर्मेटिंग और प्लेसमेंट प्राप्त किया जा सके।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


VSTM एक्सटेंशन वाली फ़ाइलें Microsoft Visio से बनाई गई टेम्प्लेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDX फ़ाइलों के विपरीत, VSTM टेम्प्लेट से बनाई गई फ़ाइलें Visual Basic for Applications (VBA) कोड में विकसित मैक्रो चलाने में सक्षम होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/image/vstm).


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
