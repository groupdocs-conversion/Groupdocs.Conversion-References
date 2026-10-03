---
title: "SpreadsheetConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file Foglio di calcolo."
type: docs
weight: 40
url: /it/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Opzioni per la conversione al tipo di file Foglio di calcolo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Inizializza una nuova istanza della classe [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
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
|  | [getSeparator()](#getSeparator--) | Specifica il separatore da utilizzare quando si converte in formati delimitati |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Inizializza una nuova istanza della classe [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


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


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Specifica il separatore da utilizzare quando si converte in formati delimitati


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatore | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

