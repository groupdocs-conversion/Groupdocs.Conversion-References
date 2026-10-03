---
title: "WordProcessingFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "वर्ड प्रोसेसिंग फ़ाइलों को परिभाषित करता है जो साधारण टेक्स्ट या रिच टेक्स्ट फ़ॉर्मेट में उपयोगकर्ता जानकारी रखती हैं।"
type: docs
weight: 28
url: /hi/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

परिभाषित करता है वर्ड प्रोसेसिंग फ़ाइलें जो उपयोगकर्ता जानकारी को साधारण पाठ या रिच टेक्स्ट फ़ॉर्मेट में रखती हैं। एक साधारण पाठ फ़ाइल फ़ॉर्मेट में अनफ़ॉर्मेटेड टेक्स्ट होता है और कोई फ़ॉन्ट या पेज सेटिंग्स आदि लागू नहीं की जा सकतीं। इसके विपरीत, रिच टेक्स्ट फ़ाइल फ़ॉर्मेट फ़ॉर्मेटिंग विकल्पों की अनुमति देता है जैसे फ़ॉन्ट प्रकार सेट करना, शैलियाँ (बोल्ड, इटैलिक, अंडरलाइन आदि), पेज मार्जिन, हेडिंग्स, बुलेट और नंबर, तथा कई अन्य फ़ॉर्मेटिंग सुविधाएँ।
निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
वर्ड प्रोसेसिंग फ़ॉर्मेट्स के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing).


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Doc](#Doc) | .doc एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न दस्तावेज़ों का प्रतिनिधित्व करती हैं। |
|
|  | [Docm](#Docm) | DOCM फ़ाइलें माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के द्वारा उत्पन्न दस्तावेज़ हैं जिनमें मैक्रो चलाने की क्षमता होती है। |
|
|  | [Docx](#Docx) | DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। |
|
|  | [Dot](#Dot) | .DOT एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। |
|
|  | [Dotm](#Dotm) | DOTM एक्सटेंशन वाली फ़ाइल माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के द्वारा बनाई गई टेम्प्लेट फ़ाइल का प्रतिनिधित्व करती है। |
|
|  | [Dotx](#Dotx) | .DOTX एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। |
|
|  | [Rtf](#Rtf) | माइक्रोसॉफ्ट द्वारा प्रस्तुत और दस्तावेज़ित, रिच टेक्स्ट फ़ॉर्मेट (RTF) अनुप्रयोगों के भीतर उपयोग के लिए फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि का प्रतिनिधित्व करता है। |
|
|  | [Odt](#Odt) | ODT फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो ओपनडॉक्यूमेंट टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित वर्ड प्रोसेसिंग एप्लिकेशन द्वारा बनाई गई हैं। |
|
|  | [Ott](#Ott) | .OTT एक्सटेंशन वाली फ़ाइलें OASIS के ओपनडॉक्यूमेंट मानक फ़ॉर्मेट के अनुरूप एप्लिकेशन द्वारा उत्पन्न टेम्प्लेट दस्तावेज़ों का प्रतिनिधित्व करती हैं। |
|
|  | [Txt](#Txt) | .TXT एक्सटेंशन वाली फ़ाइल एक टेक्स्ट दस्तावेज़ का प्रतिनिधित्व करती है जिसमें पंक्तियों के रूप में साधारण टेक्स्ट होता है। |
|
|  | [Md](#Md) | मार्कडाउन भाषा उपभाषाओं के साथ बनाई गई टेक्स्ट फ़ाइलें .MD या .MARKDOWN फ़ाइल एक्सटेंशन के साथ सहेजी जाती हैं। |
|
|  | [Ml](#Ml) | ML फ़ाइल |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


.doc एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न दस्तावेज़ों का प्रतिनिधित्व करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM फ़ाइलें माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के द्वारा उत्पन्न दस्तावेज़ हैं जिनमें मैक्रो चलाने की क्षमता होती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। 2007 से माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ प्रस्तुत, इस नए दस्तावेज़ फ़ॉर्मेट की संरचना साधारण बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दी गई थी।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


.DOT एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


DOTM एक्सटेंशन वाली फ़ाइल माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के द्वारा बनाई गई टेम्प्लेट फ़ाइल का प्रतिनिधित्व करती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


.DOTX एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


माइक्रोसॉफ्ट द्वारा प्रस्तुत और दस्तावेज़ित, रिच टेक्स्ट फ़ॉर्मेट (RTF) अनुप्रयोगों के भीतर उपयोग के लिए फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो ओपनडॉक्यूमेंट टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित वर्ड प्रोसेसिंग एप्लिकेशन द्वारा बनाई गई हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


.OTT एक्सटेंशन वाली फ़ाइलें OASIS के ओपनडॉक्यूमेंट मानक फ़ॉर्मेट के अनुरूप एप्लिकेशन द्वारा उत्पन्न टेम्प्लेट दस्तावेज़ों का प्रतिनिधित्व करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


.TXT एक्सटेंशन वाली फ़ाइल एक टेक्स्ट दस्तावेज़ का प्रतिनिधित्व करती है जिसमें पंक्तियों के रूप में साधारण टेक्स्ट होता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


Markdown भाषा के विभिन्न रूपों से निर्मित टेक्स्ट फ़ाइलें .MD या .MARKDOWN फ़ाइल एक्सटेंशन के साथ सहेजी जाती हैं। MD फ़ाइलें सादे टेक्स्ट फ़ॉर्मेट में सहेजी जाती हैं जो Markdown भाषा का उपयोग करती हैं और इसमें इनलाइन टेक्स्ट प्रतीक भी शामिल होते हैं, जो यह निर्धारित करते हैं कि टेक्स्ट को कैसे फ़ॉर्मेट किया जा सकता है जैसे इंडेंटेशन, तालिका फ़ॉर्मेटिंग, फ़ॉन्ट और हेडर। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [here](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


ML फ़ाइल


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
