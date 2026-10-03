---
title: "ConverterSettings"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce le impostazioni per personalizzare il comportamento."
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Definisce le impostazioni per personalizzare il comportamento di [Converter](../../com.groupdocs.conversion/converter).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCache()](#getCache--) | L'implementazione della cache utilizzata per memorizzare i risultati della conversione. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | L'implementazione della cache utilizzata per memorizzare i risultati della conversione. |
|
|  | [getLogger()](#getLogger--) | L'implementazione del logger utilizzata per registrare il processo di conversione. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | L'implementazione del logger utilizzata per registrare il processo di conversione. |
|
|  | [getListener()](#getListener--) | Ottiene l'implementazione del listener del convertitore utilizzata per monitorare lo stato e l'avanzamento della conversione. |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Imposta l'implementazione del listener del convertitore utilizzata per monitorare lo stato e l'avanzamento della conversione. |
|
|  | [getFontDirectories()](#getFontDirectories--) | I percorsi delle directory dei font personalizzati |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | I percorsi delle directory dei font personalizzati |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Cartella temporanea utilizzata per la conversione |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Imposta la cartella temporanea utilizzata per la conversione |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


L'implementazione della cache utilizzata per memorizzare i risultati della conversione.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


L'implementazione della cache utilizzata per memorizzare i risultati della conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


L'implementazione del logger utilizzata per registrare il processo di conversione.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


L'implementazione del logger utilizzata per registrare il processo di conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Ottiene l'implementazione del listener del convertitore utilizzata per monitorare lo stato e l'avanzamento della conversione.


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Imposta l'implementazione del listener del convertitore utilizzata per monitorare lo stato e l'avanzamento della conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Il listener del convertitore |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


I percorsi delle directory dei font personalizzati


**Returns:**
java.util.List<java.lang.String>
### getFontDirectoriesInternal() {#getFontDirectoriesInternal--}
```
public List<String> getFontDirectoriesInternal()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


I percorsi delle directory dei font personalizzati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<java.lang.String> |  |

### listConverterSettings() {#listConverterSettings--}
```
public List<String> listConverterSettings()
```




**Returns:**
java.util.List<java.lang.String>
### getTempFolder() {#getTempFolder--}
```
public String getTempFolder()
```


Cartella temporanea utilizzata per la conversione


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Imposta la cartella temporanea utilizzata per la conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

