---
title: ConversionNotSupportedException
second_title: GroupDocs.Conversion for Java API Reference
description: GroupDocs exception thrown when the conversion from source file to target file type is not supported
type: docs
weight: 10
url: /java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

GroupDocs exception thrown when the conversion from source file to target file type is not supported
## Constructors

| Constructor | Description |
| --- | --- |
| [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Default constructor |
| [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Creates an exception instance with a source FileType and a target Filetype |
| [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Creates an exception instance with a message |
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Default constructor

### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Creates an exception instance with a source FileType and a target Filetype

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | The source file type |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | The target file type |

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Creates an exception instance with a message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message |

