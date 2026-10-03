---
title: "FileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Kelas dasar tipe file"
type: docs
weight: 16
url: /id/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Kelas dasar tipe file

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FileType()](#FileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Unknown](#Unknown) | Tipe file tidak diketahui |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Format file |
|
|  | [getExtension()](#getExtension--) | Ekstensi file |
|
|  | [getFamily()](#getFamily--) | Keluarga file |
|
|  | [getDescription()](#getDescription--) | Deskripsi tipe file |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Mengembalikan FileType untuk fileName yang ditentukan |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Mendapatkan FileType untuk fileExtension yang diberikan |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Mengembalikan FileType untuk aliran dokumen yang diberikan |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Mengembalikan semua nilai enumerasi. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | Representasi string |
|
|  | [getLoadOptions()](#getLoadOptions--) | Menyiapkan opsi muat default untuk tipe file sumber |
|
|  | [getConvertOptions()](#getConvertOptions--) | Menyiapkan opsi konversi default untuk tipe file |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Konstruktor serialisasi


### Unknown {#Unknown}
```
public static final FileType Unknown
```


Tipe file tidak diketahui


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Format file


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ekstensi file


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


Keluarga file


**Returns:**
java.lang.String - Keluarga file

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Deskripsi tipe file


**Returns:**
java.lang.String - deskripsi

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Mengembalikan FileType untuk fileName yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileName | java.lang.String | Nama file |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Mendapatkan FileType untuk fileExtension yang diberikan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileExtension | java.lang.String | ekstensi file |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Mengembalikan FileType untuk aliran dokumen yang diberikan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream yang akan dipindai |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Mengembalikan semua nilai enumerasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Daftar tipe file


T
: Tipe objek yang dienumerasi.

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Representasi string


**Returns:**
java.lang.String - Representasi string dari tipe file

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


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


Menentukan apakah dua instance objek sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah dua instance objek sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berfungsi sebagai fungsi hash default.


**Returns:**
int
