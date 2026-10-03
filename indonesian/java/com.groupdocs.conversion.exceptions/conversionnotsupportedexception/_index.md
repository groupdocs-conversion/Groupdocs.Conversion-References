---
title: "ConversionNotSupportedException"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Pengecualian GroupDocs dilempar ketika konversi dari file sumber ke tipe file target tidak didukung."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Pengecualian GroupDocs dilempar ketika konversi dari file sumber ke tipe file target tidak didukung.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Konstruktor default |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Membuat sebuah instance eksepsi dengan FileType sumber dan Filetype target |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Membuat instance pengecualian dengan pesan |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Konstruktor default


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Membuat sebuah instance eksepsi dengan FileType sumber dan Filetype target


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Tipe file sumber |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Tipe file target |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Membuat instance pengecualian dengan pesan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan |
|

