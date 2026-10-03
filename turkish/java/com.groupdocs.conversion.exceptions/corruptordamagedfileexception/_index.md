---
title: "CorruptOrDamagedFileException"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Dosya bozuk veya zarar gördüğünde atılan GroupDocs istisnası"
type: docs
weight: 11
url: /tr/java/com.groupdocs.conversion.exceptions/corruptordamagedfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class CorruptOrDamagedFileException extends GroupDocsConversionException
```

Dosya bozuk veya zarar gördüğünde atılan GroupDocs istisnası

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CorruptOrDamagedFileException()](#CorruptOrDamagedFileException--) | Varsayılan yapıcı |
|
|  | [CorruptOrDamagedFileException(FileType fileType)](#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-) | Bir FileType ile bir istisna örneği oluşturur |
|
|  | [CorruptOrDamagedFileException(String message)](#CorruptOrDamagedFileException-java.lang.String-) | Bir mesaj ile bir istisna örneği oluşturur |
|
|  | [CorruptOrDamagedFileException(String message, RuntimeException exception)](#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-) | Bir mesajla bir istisna örneği oluşturur ve iç istisnayı yayar. |
|
### CorruptOrDamagedFileException() {#CorruptOrDamagedFileException--}
```
public CorruptOrDamagedFileException()
```


Varsayılan yapıcı


### CorruptOrDamagedFileException(FileType fileType) {#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-}
```
public CorruptOrDamagedFileException(FileType fileType)
```


Bir FileType ile bir istisna örneği oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Dosya türü |
|

### CorruptOrDamagedFileException(String message) {#CorruptOrDamagedFileException-java.lang.String-}
```
public CorruptOrDamagedFileException(String message)
```


Bir mesaj ile bir istisna örneği oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj |
|

### CorruptOrDamagedFileException(String message, RuntimeException exception) {#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-}
```
public CorruptOrDamagedFileException(String message, RuntimeException exception)
```


Bir mesajla bir istisna örneği oluşturur ve iç istisnayı yayar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Mesaj |
|
|  | istisna | java.lang.RuntimeException | İç istisna |
|

