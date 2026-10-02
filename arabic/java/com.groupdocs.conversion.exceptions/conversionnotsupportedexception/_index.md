---
title: "ConversionNotSupportedException"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "استثناء GroupDocs يُطرح عندما لا يكون التحويل من ملف المصدر إلى نوع الملف الهدف مدعومًا"
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

استثناء GroupDocs يُطرح عندما لا يكون التحويل من ملف المصدر إلى نوع الملف الهدف مدعومًا

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | المُنشئ الافتراضي |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | ينشئ كائن استثناء بمصدر FileType وملف هدف Filetype |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | ينشئ كائن استثناء مع رسالة |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


المُنشئ الافتراضي


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


ينشئ كائن استثناء بمصدر FileType وملف هدف Filetype


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف المصدر |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف الهدف |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


ينشئ كائن استثناء مع رسالة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | الرسالة |
|

