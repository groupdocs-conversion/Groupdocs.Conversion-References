---
title: "FileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "फ़ाइल प्रकार बेस क्लास"
type: docs
weight: 16
url: /hi/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

फ़ाइल प्रकार बेस क्लास

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [FileType()](#FileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Unknown](#Unknown) | अज्ञात फ़ाइल प्रकार |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | फ़ाइल स्वरूप |
|
|  | [getExtension()](#getExtension--) | फ़ाइल एक्सटेंशन |
|
|  | [getFamily()](#getFamily--) | फ़ाइल परिवार |
|
|  | [getDescription()](#getDescription--) | फ़ाइल प्रकार का विवरण |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | निर्दिष्ट fileName के लिए FileType लौटाता है |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | प्रदान किए गए fileExtension के लिए FileType प्राप्त करता है |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | प्रदान किए गए दस्तावेज़ स्ट्रीम के लिए FileType लौटाता है |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | सभी enumeration मान लौटाता है। |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | String प्रतिनिधित्व |
|
|  | [getLoadOptions()](#getLoadOptions--) | स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए |
|
|  | [getConvertOptions()](#getConvertOptions--) | फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Unknown {#Unknown}
```
public static final FileType Unknown
```


अज्ञात फ़ाइल प्रकार


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


फ़ाइल स्वरूप


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


फ़ाइल एक्सटेंशन


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


फ़ाइल परिवार


**Returns:**
java.lang.String - फ़ाइल परिवार

### getDescription() {#getDescription--}
```
public final String getDescription()
```


फ़ाइल प्रकार का विवरण


**Returns:**
java.lang.String - विवरण

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


निर्दिष्ट fileName के लिए FileType लौटाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | फ़ाइल नाम |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


प्रदान किए गए fileExtension के लिए FileType प्राप्त करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileExtension | java.lang.String | फ़ाइल एक्सटेंशन |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


प्रदान किए गए दस्तावेज़ स्ट्रीम के लिए FileType लौटाता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream जिसे जांचा जाएगा |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


सभी enumeration मान लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - फ़ाइल प्रकारों की सूची


T
: सूचीबद्ध वस्तु प्रकार।

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


String प्रतिनिधित्व


**Returns:**
java.lang.String - फ़ाइल प्रकार का स्ट्रिंग प्रतिनिधित्व

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
बूलियन
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
बूलियन
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
बूलियन
### hashCode() {#hashCode--}
```
public int hashCode()
```


डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है।


**Returns:**
int
