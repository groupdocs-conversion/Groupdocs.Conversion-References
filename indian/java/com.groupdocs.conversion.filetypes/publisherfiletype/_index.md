---
title: "PublisherFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "पब्लिशर दस्तावेज़ों को परिभाषित करता है।"
type: docs
weight: 24
url: /hi/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

पब्लिशर दस्तावेज़ों को परिभाषित करता है।
निम्नलिखित प्रकार शामिल हैं:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
फ़ॉन्ट फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/publisher).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Pub](#Pub) | PUB फ़ाइल Microsoft Publisher दस्तावेज़ फ़ाइल फ़ॉर्मेट है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


PUB फ़ाइल Microsoft Publisher दस्तावेज़ फ़ाइल फ़ॉर्मेट है। इसका उपयोग न्यूज़लेटर, फ़्लायर, ब्रोशर, पोस्टकार्ड आदि जैसे विभिन्न प्रकार के डिज़ाइन लेआउट दस्तावेज़ बनाने के लिए किया जाता है। PUB फ़ाइलें टेक्स्ट, रास्टर और वेक्टर छवियों को समाहित कर सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
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
