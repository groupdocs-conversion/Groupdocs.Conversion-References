---
title: "FileType"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "فئة قاعدة نوع الملف"
type: docs
weight: 16
url: /ar/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

فئة قاعدة نوع الملف

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileType()](#FileType--) | منشئ التسلسل |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Unknown](#Unknown) | نوع ملف غير معروف |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | تنسيق الملف |
|
|  | [getExtension()](#getExtension--) | امتداد الملف |
|
|  | [getFamily()](#getFamily--) | عائلة الملف |
|
|  | [getDescription()](#getDescription--) | وصف نوع الملف |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | إرجاع FileType للملف المحدد fileName |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | الحصول على FileType للامتداد المقدم fileExtension |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | إرجاع FileType لتدفق المستند المقدم |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | إرجاع جميع قيم التعداد. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | تمثيل النص |
|
|  | [getLoadOptions()](#getLoadOptions--) | إعداد خيارات التحميل الافتراضية لنوع ملف المصدر |
|
|  | [getConvertOptions()](#getConvertOptions--) | إعداد خيارات التحويل الافتراضية لنوع الملف |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


منشئ التسلسل


### Unknown {#Unknown}
```
public static final FileType Unknown
```


نوع ملف غير معروف


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


تنسيق الملف


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


امتداد الملف


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


عائلة الملف


**Returns:**
java.lang.String - عائلة الملف

### getDescription() {#getDescription--}
```
public final String getDescription()
```


وصف نوع الملف


**Returns:**
java.lang.String - الوصف

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


إرجاع FileType للملف المحدد fileName


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileName | java.lang.String | اسم الملف |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


الحصول على FileType للامتداد المقدم fileExtension


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileExtension | java.lang.String | امتداد الملف |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


إرجاع FileType لتدفق المستند المقدم


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream التي سيتم فحصها |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


إرجاع جميع قيم التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - مجموعة من أنواع الملفات


T
: نوع كائن مُعدَّد

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


تمثيل النص


**Returns:**
java.lang.String - تمثيل نصي لنوع الملف

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


إعداد خيارات التحميل الافتراضية لنوع ملف المصدر


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


إعداد خيارات التحويل الافتراضية لنوع الملف


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
منطقي
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


يحدد ما إذا كانت مثيلتين من الكائن متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
منطقي
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت مثيلتين من الكائن متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
منطقي
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة افتراضية.


**Returns:**
int
