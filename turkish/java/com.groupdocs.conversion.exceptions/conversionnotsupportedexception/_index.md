---
title: "ConversionNotSupportedException"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Kaynak dosyadan hedef dosya türüne dönüştürme desteklenmediğinde atılan GroupDocs istisnası"
type: docs
weight: 10
url: /tr/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Kaynak dosyadan hedef dosya türüne dönüştürme desteklenmediğinde atılan GroupDocs istisnası

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Varsayılan yapıcı |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Kaynak FileType ve hedef Filetype ile bir istisna örneği oluşturur. |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Bir mesaj ile bir istisna örneği oluşturur |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Varsayılan yapıcı


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Kaynak FileType ve hedef Filetype ile bir istisna örneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Kaynak dosya türü |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Hedef dosya türü |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Bir mesaj ile bir istisna örneği oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj |
|

