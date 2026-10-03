---
title: "ConversionNotSupportedException"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "GroupDocs exception kastas när konverteringen från källfil till målfiltyp inte stöds"
type: docs
weight: 10
url: /sv/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

GroupDocs exception kastas när konverteringen från källfil till målfiltyp inte stöds

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Standardkonstruktor |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Skapar en undantagsinstans med en källa FileType och en mål Filetype |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Skapar ett undantagsobjekt med ett meddelande |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Standardkonstruktor


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Skapar en undantagsinstans med en källa FileType och en mål Filetype


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Källfiltypen |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Målfiltypen |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Skapar ett undantagsobjekt med ett meddelande


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Meddelandet |
|

