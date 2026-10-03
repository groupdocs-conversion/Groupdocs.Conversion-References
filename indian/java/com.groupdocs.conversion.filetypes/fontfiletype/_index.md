---
title: "FontFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "फ़ॉन्ट दस्तावेज़ों को परिभाषित करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

फ़ॉन्ट दस्तावेज़ों को परिभाषित करता है।
निम्नलिखित प्रकार शामिल हैं:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
फ़ॉन्ट फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/font).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Ttf](#Ttf) | .ttf एक्सटेंशन वाली फ़ाइल TrueType विशिष्टताओं पर आधारित फ़ॉन्ट तकनीक के फ़ॉन्ट फ़ाइलों का प्रतिनिधित्व करती है। |
|
|  | [Eot](#Eot) | .eot एक्सटेंशन वाली फ़ाइल एक OpenType फ़ॉन्ट है जो दस्तावेज़ में एम्बेडेड होती है। |
|
|  | [Otf](#Otf) | .otf एक्सटेंशन वाली फ़ाइल OpenType फ़ॉन्ट फ़ॉर्मेट को दर्शाती है। |
|
|  | [Cff](#Cff) | .cff एक्सटेंशन वाली फ़ाइल एक कॉम्पैक्ट फ़ॉन्ट फ़ॉर्मेट है और इसे पोस्टस्क्रिप्ट टाइप 1 या CIDFont के रूप में भी जाना जाता है। |
|
|  | [Type1](#Type1) | टाइप 1 फ़ॉन्ट्स एक पुरानी Adobe तकनीक है जो डेस्कटॉप-आधारित प्रकाशन सॉफ़्टवेयर और पोस्टस्क्रिप्ट का उपयोग करने वाले प्रिंटरों में व्यापक रूप से उपयोग की जाती थी। |
|
|  | [Woff](#Woff) | .woff एक्सटेंशन वाली फ़ाइल वेब ओपन फ़ॉन्ट फ़ॉर्मेट (WOFF) पर आधारित वेब फ़ॉन्ट फ़ाइल है। |
|
|  | [Woff2](#Woff2) | .woff एक्सटेंशन वाली फ़ाइल वेब ओपन फ़ॉन्ट फ़ॉर्मेट (WOFF) पर आधारित वेब फ़ॉन्ट फ़ाइल है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


.ttf एक्सटेंशन वाली फ़ाइल TrueType विशिष्टताओं पर आधारित फ़ॉन्ट फ़ाइलों का प्रतिनिधित्व करती है। इसे मूल रूप से Apple Computer, Inc ने मैक OS के लिए डिज़ाइन और लॉन्च किया था और बाद में माइक्रोसॉफ्ट ने विंडोज OS के लिए अपनाया। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


.eot एक्सटेंशन वाली फ़ाइल एक OpenType फ़ॉन्ट है जो दस्तावेज़ में एम्बेडेड होती है। ये मुख्यतः वेब फ़ाइलों जैसे वेब पेज में उपयोग होती हैं। इसे माइक्रोसॉफ्ट ने बनाया और माइक्रोसॉफ्ट उत्पादों जैसे PowerPoint प्रस्तुति .pps फ़ाइल द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


.otf एक्सटेंशन वाली फ़ाइल OpenType फ़ॉन्ट फ़ॉर्मेट को दर्शाती है। OTF फ़ॉन्ट फ़ॉर्मेट अधिक स्केलेबल है और डिजिटल टाइपोग्राफी के लिए TTF फ़ॉर्मेट की मौजूदा सुविधाओं को विस्तारित करता है। माइक्रोसॉफ्ट और Adobe द्वारा विकसित, OTF पोस्टस्क्रिप्ट और TrueType फ़ॉन्ट फ़ॉर्मेट की सुविधाओं को मिलाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


.cff एक्सटेंशन वाली फ़ाइल एक कॉम्पैक्ट फ़ॉन्ट फ़ॉर्मेट है और इसे पोस्टस्क्रिप्ट टाइप 1 या CIDFont के रूप में भी जाना जाता है। CFF कई फ़ॉन्ट्स को एक ही इकाई, जिसे फ़ॉन्टसेट कहा जाता है, में संग्रहीत करने के लिए कंटेनर के रूप में कार्य करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


टाइप 1 फ़ॉन्ट्स एक पुरानी Adobe तकनीक है जो डेस्कटॉप-आधारित प्रकाशन सॉफ़्टवेयर और पोस्टस्क्रिप्ट का उपयोग करने वाले प्रिंटरों में व्यापक रूप से उपयोग की जाती थी। हालांकि टाइप 1 फ़ॉन्ट्स कई आधुनिक प्लेटफ़ॉर्म, वेब ब्राउज़र और मोबाइल ऑपरेटिंग सिस्टम में समर्थित नहीं हैं, लेकिन कुछ ऑपरेटिंग सिस्टम में अभी भी समर्थित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


.woff एक्सटेंशन वाली फ़ाइल वेब ओपन फ़ॉन्ट फ़ॉर्मेट (WOFF) पर आधारित वेब फ़ॉन्ट फ़ाइल है। इसमें फ़ॉर्मेट-विशिष्ट संपीड़ित कंटेनर होता है जो TrueType (.TTF) या OpenType (.OTT) फ़ॉन्ट प्रकारों में से किसी एक पर आधारित होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


.woff एक्सटेंशन वाली फ़ाइल वेब ओपन फ़ॉन्ट फ़ॉर्मेट (WOFF) पर आधारित वेब फ़ॉन्ट फ़ाइल है। इसमें फ़ॉर्मेट-विशिष्ट संपीड़ित कंटेनर होता है जो TrueType (.TTF) या OpenType (.OTT) फ़ॉन्ट प्रकारों में से किसी एक पर आधारित होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/font/woff/).


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
