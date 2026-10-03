---
title: "ConversionPair"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "रूपांतरण जोड़ी का प्रतिनिधित्व करता है"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

रूपांतरण जोड़ी का प्रतिनिधित्व करता है

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [NULL](#NULL) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | प्राथमिक रूपांतरण जोड़ी बनाता है |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | प्राथमिक रूपांतरण जोड़े बनाता है |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | द्वितीयक रूपांतरण जोड़ी बनाता है |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | द्वितीयक रूपांतरण जोड़े बनाता है |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | समानता घटक |
|
|  | [toString()](#toString--) | रूपांतरण जोड़ी स्ट्रिंग प्रतिनिधित्व |
|
|  | [getSource()](#getSource--) | स्रोत फ़ाइल प्रारूप |
|
|  | [getTarget()](#getTarget--) | लक्ष्य फ़ाइल प्रारूप |
|
|  | [isPrimary()](#isPrimary--) | प्राथमिक रूपांतरण जोड़ी या नहीं |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


प्राथमिक रूपांतरण जोड़ी बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | स्रोत |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | लक्ष्य |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


प्राथमिक रूपांतरण जोड़े बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्रोत | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | स्रोत फ़ाइल प्रकार |
|
|  | लक्ष्य | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | लक्ष्य फ़ाइल प्रकार |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - प्राथमिक रूपांतरण जोड़े

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्रोत | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| लक्ष्य | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


द्वितीयक रूपांतरण जोड़ी बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | स्रोत फ़ाइल प्रकार |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | लक्ष्य फ़ाइल प्रकार |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


द्वितीयक रूपांतरण जोड़े बनाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्रोत | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | स्रोत फ़ाइल प्रकार |
|
|  | लक्ष्य | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | लक्ष्य फ़ाइल प्रकार |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - द्वितीयक रूपांतरण जोड़े

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


समानता घटक


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - समानता घटक

### toString() {#toString--}
```
public String toString()
```


रूपांतरण जोड़ी स्ट्रिंग प्रतिनिधित्व


**Returns:**
java.lang.String - स्ट्रिंग

### getSource() {#getSource--}
```
public FileType getSource()
```


स्रोत फ़ाइल प्रारूप


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


लक्ष्य फ़ाइल प्रारूप


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


प्राथमिक रूपांतरण जोड़ी या नहीं


**Returns:**
boolean - यदि प्राथमिक हो तो true, अन्यथा नहीं

