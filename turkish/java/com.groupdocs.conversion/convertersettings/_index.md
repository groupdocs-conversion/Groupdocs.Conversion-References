---
title: "ConverterSettings"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Davranışı özelleştirmek için ayarları tanımlar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Davranışı özelleştirmek için [Converter](../../com.groupdocs.conversion/converter) ayarlarını tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCache()](#getCache--) | Dönüştürme sonuçlarını depolamak için kullanılan önbellek uygulaması. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | Dönüştürme sonuçlarını depolamak için kullanılan önbellek uygulaması. |
|
|  | [getLogger()](#getLogger--) | Dönüştürme sürecini kaydetmek için kullanılan günlük kaydedici uygulaması. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | Dönüştürme sürecini kaydetmek için kullanılan günlük kaydedici uygulaması. |
|
|  | [getListener()](#getListener--) | Dönüştürme durumu ve ilerlemesini izlemek için kullanılan dönüştürücü dinleyici uygulamasını alır |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Dönüştürme durumu ve ilerlemesini izlemek için kullanılan dönüştürücü dinleyici uygulamasını ayarlar |
|
|  | [getFontDirectories()](#getFontDirectories--) | Özel yazı tipi dizin yolları |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Özel yazı tipi dizin yolları |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Dönüştürme için kullanılan geçici klasör |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Dönüştürme için kullanılan geçici klasörü ayarlar |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Dönüştürme sonuçlarını depolamak için kullanılan önbellek uygulaması.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


Dönüştürme sonuçlarını depolamak için kullanılan önbellek uygulaması.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Dönüştürme sürecini kaydetmek için kullanılan günlük kaydedici uygulaması.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Dönüştürme sürecini kaydetmek için kullanılan günlük kaydedici uygulaması.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Dönüştürme durumu ve ilerlemesini izlemek için kullanılan dönüştürücü dinleyici uygulamasını alır


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Dönüştürme durumu ve ilerlemesini izlemek için kullanılan dönüştürücü dinleyici uygulamasını ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Dönüştürücü dinleyicisi |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Özel yazı tipi dizin yolları


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


Özel yazı tipi dizin yolları


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.String> |  |

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


Dönüştürme için kullanılan geçici klasör


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Dönüştürme için kullanılan geçici klasörü ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

