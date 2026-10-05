---
title: "TargetConversion"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Representa la conversión de destino posible y una bandera que indica si es primaria o secundaria"
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Representa la conversión de destino posible y una bandera que indica si es primaria o secundaria
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) | Formato de documento de destino |
| [isPrimary()](#isPrimary--) | ¿La conversión es primaria? |
| [getConvertOptions()](#getConvertOptions--) | Opciones de conversión predefinidas que podrían usarse para convertir al tipo actual |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Formato de documento de destino

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


¿La conversión es primaria?

**Returns:**
boolean - `true` si es primaria
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predefinidas que podrían usarse para convertir al tipo actual

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options
