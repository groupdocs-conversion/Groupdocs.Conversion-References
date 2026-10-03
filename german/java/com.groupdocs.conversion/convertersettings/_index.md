---
title: "ConverterSettings"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Einstellungen zum Anpassen des Verhaltens."
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Definiert Einstellungen zum Anpassen des Verhaltens von [Converter](../../com.groupdocs.conversion/converter).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCache()](#getCache--) | Die Cache-Implementierung, die zum Speichern von Konvertierungsergebnissen verwendet wird. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | Die Cache-Implementierung, die zum Speichern von Konvertierungsergebnissen verwendet wird. |
|
|  | [getLogger()](#getLogger--) | Die Logger-Implementierung, die zum Protokollieren des Konvertierungsprozesses verwendet wird. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | Die Logger-Implementierung, die zum Protokollieren des Konvertierungsprozesses verwendet wird. |
|
|  | [getListener()](#getListener--) | Ruft die Implementierung des Converter-Listeners ab, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird. |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Setzt die Implementierung des Converter-Listeners, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Die Pfade zu benutzerdefinierten Schriftartverzeichnissen |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Die Pfade zu benutzerdefinierten Schriftartverzeichnissen |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Temporärer Ordner, der für die Konvertierung verwendet wird |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Setzt den temporären Ordner, der für die Konvertierung verwendet wird |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Die Cache-Implementierung, die zum Speichern von Konvertierungsergebnissen verwendet wird.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


Die Cache-Implementierung, die zum Speichern von Konvertierungsergebnissen verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Die Logger-Implementierung, die zum Protokollieren des Konvertierungsprozesses verwendet wird.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Die Logger-Implementierung, die zum Protokollieren des Konvertierungsprozesses verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Ruft die Implementierung des Converter-Listeners ab, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird.


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Setzt die Implementierung des Converter-Listeners, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Der Converter-Listener |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Die Pfade zu benutzerdefinierten Schriftartverzeichnissen


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


Die Pfade zu benutzerdefinierten Schriftartverzeichnissen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<java.lang.String> |  |

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


Temporärer Ordner, der für die Konvertierung verwendet wird


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Setzt den temporären Ordner, der für die Konvertierung verwendet wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

