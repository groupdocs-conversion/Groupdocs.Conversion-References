---
title: ConverterSettings
second_title: GroupDocs.Conversion for Java API Reference
description: Defines settings for customizing  behaviour.
type: docs
weight: 11
url: /java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Defines settings for customizing [Converter](../../com.groupdocs.conversion/converter) behaviour.
## Constructors

| Constructor | Description |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCache()](#getCache--) | The cache implementation used for storing conversion results. |
| [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | The cache implementation used for storing conversion results. |
| [getLogger()](#getLogger--) | The logger implementation used for logging conversion process. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | The logger implementation used for logging conversion process. |
| [getListener()](#getListener--) | Gets the converter listener implementation used for monitoring conversion status and progress |
| [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Sets the converter listener implementation used for monitoring conversion status and progress |
| [getFontDirectories()](#getFontDirectories--) | The custom font directories paths |
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
| [listConverterSettings()](#listConverterSettings--) |  |
| [getTempFolder()](#getTempFolder--) | Temp folder used for conversion |
| [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Sets Temp folder used for conversion |
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


The cache implementation used for storing conversion results.

**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


The cache implementation used for storing conversion results.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


The logger implementation used for logging conversion process.

**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


The logger implementation used for logging conversion process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Gets the converter listener implementation used for monitoring conversion status and progress

**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener
### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Sets the converter listener implementation used for monitoring conversion status and progress

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | The converter listener |

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


The custom font directories paths

**Returns:**
java.util.List<java.lang.String>
### getFontDirectoriesInternal() {#getFontDirectoriesInternal--}
```
public List<String> getFontDirectoriesInternal()
```




**Returns:**
java.util.List<java.lang.String>
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


Temp folder used for conversion

**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Sets Temp folder used for conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

