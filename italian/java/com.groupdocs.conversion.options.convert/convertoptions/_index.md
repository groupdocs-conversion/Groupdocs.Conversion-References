---
title: "ConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "La classe generale delle opzioni di conversione."
type: docs
weight: 12
url: /it/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

La classe generale delle opzioni di conversione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza delle opzioni corrente. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Ottiene il tipo di file desiderato in cui il documento di input deve essere convertito.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona l'istanza delle opzioni corrente.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | TFileType |  |

