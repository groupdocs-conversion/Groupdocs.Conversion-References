---
title: "PossibleConversions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "विशिष्ट स्रोत फ़ाइल फ़ॉर्मेट के लिए समर्थित रूपांतरण जोड़ों का मानचित्रण दर्शाता है"
type: docs
weight: 13
url: /hi/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

विशिष्ट स्रोत फ़ाइल फ़ॉर्मेट के लिए समर्थित रूपांतरण जोड़ों का मानचित्रण दर्शाता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | निर्दिष्ट स्रोत फ़ाइल प्रारूप के लिए संभावित रूपांतरण सूची बनाता है |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [NULL](#NULL) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | पूर्वनिर्धारित लोड विकल्प जो वर्तमान प्रकार से रूपांतरण के लिए उपयोग किए जा सकते हैं |
|
|  | [getAll()](#getAll--) | सभी लक्ष्य फ़ाइल प्रकार और प्राथमिक/द्वितीयक फ़्लैग |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | निर्दिष्ट लक्ष्य फ़ाइल प्रकार के लिए लक्ष्य रूपांतरण लौटाता है |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | प्राथमिक लक्ष्य फ़ाइल प्रकार |
|
|  | [getSecondary()](#getSecondary--) | द्वितीयक लक्ष्य फ़ाइल प्रकार |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | रूपांतरण जोड़ी जोड़ें |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | लक्ष्य फ़ाइल प्रकार के लिए वर्तमान सूची में रूपांतरण जोड़ी खोजें |
|
|  | [getSource()](#getSource--) | स्रोत फ़ाइल प्रारूप |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


निर्दिष्ट स्रोत फ़ाइल प्रारूप के लिए संभावित रूपांतरण सूची बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | स्रोत फ़ाइल प्रकार |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


पूर्वनिर्धारित लोड विकल्प जो वर्तमान प्रकार से रूपांतरण के लिए उपयोग किए जा सकते हैं


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


सभी लक्ष्य फ़ाइल प्रकार और प्राथमिक/द्वितीयक फ़्लैग


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) का इटेरेबल

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


निर्दिष्ट लक्ष्य फ़ाइल प्रकार के लिए लक्ष्य रूपांतरण लौटाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | लक्ष्य फ़ाइल प्रकार |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extension | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


प्राथमिक लक्ष्य फ़ाइल प्रकार


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - प्राथमिक लक्ष्य फ़ाइल प्रकार

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


द्वितीयक लक्ष्य फ़ाइल प्रकार


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - द्वितीयक लक्ष्य फ़ाइल प्रकार

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


रूपांतरण जोड़ी जोड़ें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | रूपांतरण युग्म |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


लक्ष्य फ़ाइल प्रकार के लिए वर्तमान सूची में रूपांतरण जोड़ी खोजें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | लक्ष्य फ़ाइल प्रकार |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


स्रोत फ़ाइल प्रारूप


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

