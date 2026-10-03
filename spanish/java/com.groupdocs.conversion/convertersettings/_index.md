---
title: "ConverterSettings"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define la configuración para personalizar el comportamiento."
type: docs
weight: 11
url: /es/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Define la configuración para personalizar el comportamiento del [Converter](../../com.groupdocs.conversion/converter).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getCache()](#getCache--) | La implementación de caché utilizada para almacenar los resultados de la conversión. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | La implementación de caché utilizada para almacenar los resultados de la conversión. |
|
|  | [getLogger()](#getLogger--) | La implementación del registrador utilizada para registrar el proceso de conversión. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | La implementación del registrador utilizada para registrar el proceso de conversión. |
|
|  | [getListener()](#getListener--) | Obtiene la implementación del listener del convertidor utilizada para monitorear el estado y progreso de la conversión |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Establece la implementación del listener del convertidor utilizada para monitorear el estado y progreso de la conversión |
|
|  | [getFontDirectories()](#getFontDirectories--) | Las rutas de los directorios de fuentes personalizadas |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Las rutas de los directorios de fuentes personalizadas |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Carpeta temporal utilizada para la conversión |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Establece la carpeta temporal utilizada para la conversión |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


La implementación de caché utilizada para almacenar los resultados de la conversión.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


La implementación de caché utilizada para almacenar los resultados de la conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


La implementación del registrador utilizada para registrar el proceso de conversión.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


La implementación del registrador utilizada para registrar el proceso de conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Obtiene la implementación del listener del convertidor utilizada para monitorear el estado y progreso de la conversión


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Establece la implementación del listener del convertidor utilizada para monitorear el estado y progreso de la conversión


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | El listener del convertidor |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Las rutas de los directorios de fuentes personalizadas


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


Las rutas de los directorios de fuentes personalizadas


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.String> |  |

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


Carpeta temporal utilizada para la conversión


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Establece la carpeta temporal utilizada para la conversión


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

