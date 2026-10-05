---
title: "ConverterSettings"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert instellingen voor het aanpassen van het gedrag."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Definieert instellingen voor het aanpassen van het gedrag van [Converter](../../com.groupdocs.conversion/converter).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCache()](#getCache--) | De cache-implementatie die wordt gebruikt voor het opslaan van conversieresultaten. |
| [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | De cache-implementatie die wordt gebruikt voor het opslaan van conversieresultaten. |
| [getLogger()](#getLogger--) | De logger-implementatie die wordt gebruikt voor het loggen van het conversieproces. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | De logger-implementatie die wordt gebruikt voor het loggen van het conversieproces. |
| [getListener()](#getListener--) | Haalt de converter‑listener‑implementatie op die wordt gebruikt voor het bewaken van de conversiestatus en voortgang. |
| [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Stelt de converter‑listener‑implementatie in die wordt gebruikt voor het bewaken van de conversiestatus en voortgang. |
| [getFontDirectories()](#getFontDirectories--) | De paden van aangepaste lettertype‑mappen. |
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
| [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | De paden van aangepaste lettertype‑mappen. |
| [listConverterSettings()](#listConverterSettings--) |  |
| [getTempFolder()](#getTempFolder--) | Tijdelijke map die wordt gebruikt voor conversie. |
| [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Stelt de tijdelijke map in die wordt gebruikt voor conversie. |
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


De cache-implementatie die wordt gebruikt voor het opslaan van conversieresultaten.

**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


De cache-implementatie die wordt gebruikt voor het opslaan van conversieresultaten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


De logger-implementatie die wordt gebruikt voor het loggen van het conversieproces.

**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


De logger-implementatie die wordt gebruikt voor het loggen van het conversieproces.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Haalt de converter‑listener‑implementatie op die wordt gebruikt voor het bewaken van de conversiestatus en voortgang.

**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener
### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Stelt de converter‑listener‑implementatie in die wordt gebruikt voor het bewaken van de conversiestatus en voortgang.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | De converter‑listener. |

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


De paden van aangepaste lettertype‑mappen.

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


De paden van aangepaste lettertype‑mappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.List<java.lang.String> |  |

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


Tijdelijke map die wordt gebruikt voor conversie.

**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Stelt de tijdelijke map in die wordt gebruikt voor conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

