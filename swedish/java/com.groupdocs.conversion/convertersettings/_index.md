---
title: "ConverterSettings"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar inställningar för att anpassa beteendet."
type: docs
weight: 11
url: /sv/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Definierar inställningar för att anpassa [Converter](../../com.groupdocs.conversion/converter) beteendet.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCache()](#getCache--) | Cache‑implementeringen som används för att lagra konverteringsresultat. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | Cache‑implementeringen som används för att lagra konverteringsresultat. |
|
|  | [getLogger()](#getLogger--) | Logger‑implementeringen som används för att logga konverteringsprocessen. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | Logger‑implementeringen som används för att logga konverteringsprocessen. |
|
|  | [getListener()](#getListener--) | Hämtar converter listener‑implementeringen som används för att övervaka konverteringsstatus och framsteg |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Ställer in converter listener‑implementeringen som används för att övervaka konverteringsstatus och framsteg |
|
|  | [getFontDirectories()](#getFontDirectories--) | Sökvägar till anpassade teckensnittskataloger |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Sökvägar till anpassade teckensnittskataloger |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Tempmapp som används för konvertering |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Ställer in tempmapp som används för konvertering |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Cache‑implementeringen som används för att lagra konverteringsresultat.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


Cache‑implementeringen som används för att lagra konverteringsresultat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Logger‑implementeringen som används för att logga konverteringsprocessen.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Logger‑implementeringen som används för att logga konverteringsprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Hämtar converter listener‑implementeringen som används för att övervaka konverteringsstatus och framsteg


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Ställer in converter listener‑implementeringen som används för att övervaka konverteringsstatus och framsteg


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Converter listener |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Sökvägar till anpassade teckensnittskataloger


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


Sökvägar till anpassade teckensnittskataloger


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<java.lang.String> |  |

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


Tempmapp som används för konvertering


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Ställer in tempmapp som används för konvertering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

