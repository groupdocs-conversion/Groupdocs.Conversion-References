---
title: "ConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Die allgemeine Konvertierungsoptionenklasse."
type: docs
weight: 12
url: /de/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

Die allgemeine Konvertierungsoptionenklasse.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
|
|  | [deepClone()](#deepClone--) | Klont die aktuelle Optionsinstanz. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Ermittelt den gewünschten Dateityp, in den das Eingabedokument konvertiert werden soll.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klont die aktuelle Optionsinstanz.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | TFileType |  |

