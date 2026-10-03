---
title: "ConverterSettings"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku."
type: docs
weight: 11
url: /id/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Mendefinisikan pengaturan untuk menyesuaikan perilaku [Converter](../../com.groupdocs.conversion/converter).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCache()](#getCache--) | Implementasi cache yang digunakan untuk menyimpan hasil konversi. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | Implementasi cache yang digunakan untuk menyimpan hasil konversi. |
|
|  | [getLogger()](#getLogger--) | Implementasi logger yang digunakan untuk mencatat proses konversi. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | Implementasi logger yang digunakan untuk mencatat proses konversi. |
|
|  | [getListener()](#getListener--) | Mendapatkan implementasi listener konverter yang digunakan untuk memantau status dan kemajuan konversi |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Mengatur implementasi listener konverter yang digunakan untuk memantau status dan kemajuan konversi |
|
|  | [getFontDirectories()](#getFontDirectories--) | Jalur direktori font khusus |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Jalur direktori font khusus |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Folder sementara yang digunakan untuk konversi |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Mengatur folder sementara yang digunakan untuk konversi |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Implementasi cache yang digunakan untuk menyimpan hasil konversi.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


Implementasi cache yang digunakan untuk menyimpan hasil konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Implementasi logger yang digunakan untuk mencatat proses konversi.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Implementasi logger yang digunakan untuk mencatat proses konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Mendapatkan implementasi listener konverter yang digunakan untuk memantau status dan kemajuan konversi


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Mengatur implementasi listener konverter yang digunakan untuk memantau status dan kemajuan konversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Listener konverter |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Jalur direktori font khusus


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


Jalur direktori font khusus


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<java.lang.String> |  |

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


Folder sementara yang digunakan untuk konversi


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Mengatur folder sementara yang digunakan untuk konversi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

