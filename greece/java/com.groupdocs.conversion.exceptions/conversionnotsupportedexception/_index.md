---
title: "ConversionNotSupportedException"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Εξαίρεση GroupDocs που ρίχνεται όταν η μετατροπή από το αρχείο προέλευσης στον τύπο αρχείου προορισμού δεν υποστηρίζεται"
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Εξαίρεση GroupDocs που ρίχνεται όταν η μετατροπή από το αρχείο προέλευσης στον τύπο αρχείου προορισμού δεν υποστηρίζεται

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Προεπιλεγμένος κατασκευαστής |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Δημιουργεί μια παρουσία εξαίρεσης με πηγή FileType και προορισμό Filetype |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Δημιουργεί ένα στιγμιότυπο εξαίρεσης με ένα μήνυμα |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Προεπιλεγμένος κατασκευαστής


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Δημιουργεί μια παρουσία εξαίρεσης με πηγή FileType και προορισμό Filetype


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Ο τύπος αρχείου πηγής |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Ο τύπος αρχείου προορισμού |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Δημιουργεί ένα στιγμιότυπο εξαίρεσης με ένα μήνυμα


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα |
|

