---
title: "ConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "La clase general de opciones de conversión."
type: docs
weight: 12
url: /es/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

La clase general de opciones de conversión.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
|
|  | [deepClone()](#deepClone--) | Clona la instancia actual de opciones. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Obtiene el tipo de archivo deseado al que debe convertirse el documento de entrada.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


El tipo de archivo deseado al que debe convertirse el documento de entrada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona la instancia actual de opciones.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


El tipo de archivo deseado al que debe convertirse el documento de entrada.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


El tipo de archivo deseado al que debe convertirse el documento de entrada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | TFileType |  |

