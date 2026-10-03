---
title: "ConversionNotSupportedException"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "GroupDocs‑exceptie die wordt gegooid wanneer de conversie van bronbestand naar doelformaat niet wordt ondersteund."
type: docs
weight: 10
url: /nl/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

GroupDocs‑exceptie die wordt gegooid wanneer de conversie van bronbestand naar doelformaat niet wordt ondersteund.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Standaardconstructor |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Maakt een exception‑instantie met een bron‑FileType en een doel‑Filetype |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Maakt een exceptie‑instantie aan met een bericht |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Standaardconstructor


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Maakt een exception‑instantie met een bron‑FileType en een doel‑Filetype


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Het bron‑bestandstype |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Het doel‑bestandstype |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Maakt een exceptie‑instantie aan met een bericht


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bericht | java.lang.String | Het bericht |
|

