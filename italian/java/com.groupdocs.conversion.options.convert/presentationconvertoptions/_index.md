---
title: "PresentationConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Descrive le opzioni per la conversione al tipo di file Presentazione."
type: docs
weight: 33
url: /it/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Descrive le opzioni per la conversione al tipo di file Presentazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Inizializza una nuova istanza della classe [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta questa proprietà se desideri proteggere il documento convertito con una password. |
|
|  | [getZoom()](#getZoom--) | Specifica il livello di zoom in percentuale. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specifica il livello di zoom in percentuale. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Inizializza una nuova istanza della classe [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Imposta questa proprietà se desideri proteggere il documento convertito con una password.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta questa proprietà se desideri proteggere il documento convertito con una password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.
Lo zoom predefinito è supportato fino a Microsoft Powerpoint 2010. A partire da Microsoft Powerpoint 2013 lo zoom predefinito non viene più impostato sul documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.
Lo zoom predefinito è supportato fino a Microsoft Powerpoint 2010. A partire da Microsoft Powerpoint 2013 lo zoom predefinito non viene più impostato sul documento, ma sembra utilizzare il fattore di zoom dell'ultimo documento aperto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

