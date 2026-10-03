---
title: "RtfOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file RTF."
type: docs
weight: 39
url: /it/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Opzioni per la conversione al tipo di file RTF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Specifica se le parole chiave per "old readers" sono scritte in RTF o meno. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Specifica se le parole chiave per "old readers" sono scritte in RTF o meno. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Specifica se le parole chiave per "old readers" sono scritte in RTF o meno.
Questo può influire significativamente sulla dimensione del documento RTF. Il valore predefinito è False.


**Returns:**
booleano
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Specifica se le parole chiave per "old readers" sono scritte in RTF o meno.
Questo può influire significativamente sulla dimensione del documento RTF. Il valore predefinito è False.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

