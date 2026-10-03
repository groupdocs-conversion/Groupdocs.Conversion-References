---
title: "TargetConversion"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta la conversione di destinazione possibile e un flag che indica se è primaria o secondaria"
type: docs
weight: 14
url: /it/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Rappresenta la conversione di destinazione possibile e un flag che indica se è primaria o secondaria

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Formato del documento di destinazione |
|
|  | [isPrimary()](#isPrimary--) | La conversione è primaria |
|
|  | [getConvertOptions()](#getConvertOptions--) | Opzioni di conversione predefinite che possono essere usate per convertire al tipo corrente |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Formato del documento di destinazione


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


La conversione è primaria


**Returns:**
boolean - `true` se primaria

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opzioni di conversione predefinite che possono essere usate per convertire al tipo corrente


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

