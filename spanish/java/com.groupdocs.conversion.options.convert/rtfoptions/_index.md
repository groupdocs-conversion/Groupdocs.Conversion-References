---
title: "RtfOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para la conversión al tipo de archivo RTF."
type: docs
weight: 39
url: /es/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Opciones para la conversión al tipo de archivo RTF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Especifica si las palabras clave para "old readers" se escriben en RTF o no. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Especifica si las palabras clave para "old readers" se escriben en RTF o no. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Especifica si las palabras clave para "old readers" se escriben en RTF o no.
Esto puede afectar significativamente el tamaño del documento RTF. El valor predeterminado es False.


**Returns:**
booleano
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Especifica si las palabras clave para "old readers" se escriben en RTF o no.
Esto puede afectar significativamente el tamaño del documento RTF. El valor predeterminado es False.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

