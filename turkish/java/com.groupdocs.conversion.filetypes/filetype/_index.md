---
title: "FileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Dosya türü temel sınıfı"
type: docs
weight: 16
url: /tr/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Dosya türü temel sınıfı

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FileType()](#FileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Unknown](#Unknown) | Bilinmeyen dosya türü |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Dosya formatı |
|
|  | [getExtension()](#getExtension--) | Dosya uzantısı |
|
|  | [getFamily()](#getFamily--) | Dosya ailesi |
|
|  | [getDescription()](#getDescription--) | Dosya türünün açıklaması |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Belirtilen dosya adı için FileType döndürür |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Sağlanan dosya uzantısı için FileType alır |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Sağlanan belge akışı için FileType döndürür |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Tüm enum değerlerini döndürür. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | Dize temsili |
|
|  | [getLoadOptions()](#getLoadOptions--) | Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı |
|
|  | [getConvertOptions()](#getConvertOptions--) | Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Serileştirme yapıcısı


### Unknown {#Unknown}
```
public static final FileType Unknown
```


Bilinmeyen dosya türü


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Dosya formatı


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Dosya uzantısı


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


Dosya ailesi


**Returns:**
java.lang.String - Dosya ailesi

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Dosya türünün açıklaması


**Returns:**
java.lang.String - açıklama

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Belirtilen dosya adı için FileType döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileName | java.lang.String | Dosya adı |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Sağlanan dosya uzantısı için FileType alır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileExtension | java.lang.String | dosya uzantısı |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Sağlanan belge akışı için FileType döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream incelenecek |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Tüm enum değerlerini döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Dosya türlerinin listesi


T
: Sıralı nesne türü.

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Dize temsili


**Returns:**
java.lang.String - Dosya türünün dize temsili

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
boolean
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


İki nesne örneğinin eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki nesne örneğinin eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Varsayılan karma işlevi olarak hizmet verir.


**Returns:**
int
