---
title: "EBookFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है, जो 3D ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2D या 3D डिज़ाइन शामिल कर सकते हैं।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है जो 3d ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2d या 3d डिज़ाइन शामिल कर सकते हैं।
निम्नलिखित प्रकार शामिल हैं:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
CAD फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/cad).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Epub](#Epub) | EPUB एक्सटेंशन एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। |
|
|  | [Mobi](#Mobi) | MOBI फ़ाइल फ़ॉर्मेट सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट में से एक है। |
|
|  | [Azw3](#Azw3) | AZW3, जिसे Kindle Format 8 (KF8) के नाम से भी जाना जाता है, Amazon Kindle डिवाइसों के लिए विकसित AZW ईबुक डिजिटल फ़ाइल फ़ॉर्मेट का संशोधित संस्करण है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB एक्सटेंशन एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। यह फ़ॉर्मेट अब इतना सामान्य हो गया है कि यह कई ई-रीडर और सॉफ़्टवेयर अनुप्रयोगों द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


MOBI फ़ाइल फ़ॉर्मेट सबसे अधिक उपयोग किए जाने वाले ईबुक फ़ाइल फ़ॉर्मेट में से एक है। यह फ़ॉर्मेट पुराने OEB (Open Ebook Format) फ़ॉर्मेट में सुधार है और Mobipocket Reader के लिए स्वामित्व फ़ॉर्मेट के रूप में उपयोग किया जाता था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, जिसे Kindle Format 8 (KF8) के नाम से भी जाना जाता है, Amazon Kindle डिवाइसों के लिए विकसित AZW ईबुक डिजिटल फ़ाइल फ़ॉर्मेट का संशोधित संस्करण है। यह फ़ॉर्मेट पुराने AZW फ़ाइलों में सुधार है और केवल Kindle Fire डिवाइसों पर उपयोग होता है, साथ ही पूर्वज फ़ाइल फ़ॉर्मेट जैसे MOBI और AZW के साथ बैकवर्ड संगतता रखता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/ebook/azw3/).


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
