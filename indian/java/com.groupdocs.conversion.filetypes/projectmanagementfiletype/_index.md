---
title: "ProjectManagementFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "परियोजना प्रबंधन सॉफ़्टवेयर जैसे Microsoft Project, Primavera P6 आदि द्वारा निर्मित प्रोजेक्ट फ़ाइल फ़ॉर्मेट को परिभाषित करता है।"
type: docs
weight: 23
url: /hi/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

परियोजना प्रबंधन सॉफ़्टवेयर जैसे Microsoft Project, Primavera P6 आदि द्वारा निर्मित प्रोजेक्ट फ़ाइल फ़ॉर्मेट को परिभाषित करता है। एक प्रोजेक्ट फ़ाइल कार्यों, संसाधनों और उनके शेड्यूलिंग का संग्रह है जो उत्पाद या सेवा के रूप में मापनीय आउटपुट प्राप्त करने के लिए उपयोग किया जाता है।
परियोजना प्रबंधन दस्तावेज़। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
परियोजना प्रबंधन फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Mpt](#Mpt) | Microsoft Project टेम्पलेट फ़ाइलें, .MPP फ़ाइलें बनाने के लिए बुनियादी जानकारी और संरचना के साथ दस्तावेज़ सेटिंग्स रखती हैं। |
|
|  | [Mpp](#Mpp) | MPP Microsoft Project डेटा फ़ाइल है जो परियोजना प्रबंधन से संबंधित जानकारी को एकीकृत तरीके से संग्रहीत करती है। |
|
|  | [Mpx](#Mpx) | Microsoft Exchange फ़ाइल फ़ॉर्मेट, एक ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों के बीच प्रोजेक्ट जानकारी के स्थानांतरण के लिए उपयोग किया जाता है जो MPX फ़ाइल फ़ॉर्मेट का समर्थन करते हैं, जैसे Primavera Project Planner, Sciforma और Timerline Precision Estimating। |
|
|  | [Xer](#Xer) | XER फ़ाइल फ़ॉर्मेट Primavera P6 परियोजना योजना और प्रबंधन अनुप्रयोग द्वारा उपयोग किया जाने वाला एक स्वामित्व वाला प्रोजेक्ट फ़ाइल फ़ॉर्मेट है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project टेम्पलेट फ़ाइलें, .MPP फ़ाइलें बनाने के लिए बुनियादी जानकारी और संरचना के साथ दस्तावेज़ सेटिंग्स रखती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP Microsoft Project डेटा फ़ाइल है जो परियोजना प्रबंधन से संबंधित जानकारी को एकीकृत तरीके से संग्रहीत करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange फ़ाइल फ़ॉर्मेट, एक ASCII फ़ाइल फ़ॉर्मेट है जो Microsoft Project (MSP) और अन्य अनुप्रयोगों के बीच प्रोजेक्ट जानकारी के स्थानांतरण के लिए उपयोग किया जाता है जो MPX फ़ाइल फ़ॉर्मेट का समर्थन करते हैं, जैसे Primavera Project Planner, Sciforma और Timerline Precision Estimating।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


XER फ़ाइल फ़ॉर्मेट Primavera P6 परियोजना योजना और प्रबंधन अनुप्रयोग द्वारा उपयोग किया जाने वाला एक स्वामित्व वाला प्रोजेक्ट फ़ाइल फ़ॉर्मेट है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
