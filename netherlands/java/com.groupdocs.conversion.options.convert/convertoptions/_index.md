---
title: "ConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "De algemene conversieoptiesklasse."
type: docs
weight: 12
url: /nl/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

De algemene conversieoptiesklasse.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
|
|  | [deepClone()](#deepClone--) | Kloont de huidige opties‑instantie. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Haalt het gewenste bestandstype op waarnaar het invoerdocument moet worden geconverteerd.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloont de huidige opties‑instantie.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | TFileType |  |

