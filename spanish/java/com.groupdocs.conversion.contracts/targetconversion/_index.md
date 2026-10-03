---
title: "TargetConversion"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa la conversión objetivo posible y una bandera que indica si es primaria o secundaria."
type: docs
weight: 14
url: /es/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Representa la conversión objetivo posible y una bandera que indica si es primaria o secundaria.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Formato de documento objetivo |
|
|  | [isPrimary()](#isPrimary--) | ¿Es la conversión primaria? |
|
|  | [getConvertOptions()](#getConvertOptions--) | Opciones de conversión predefinidas que podrían usarse para convertir al tipo actual |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Formato de documento objetivo


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


¿Es la conversión primaria?


**Returns:**
booleano - `true` si es primaria

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predefinidas que podrían usarse para convertir al tipo actual


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

