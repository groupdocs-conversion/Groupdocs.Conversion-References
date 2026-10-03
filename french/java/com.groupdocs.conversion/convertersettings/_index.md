---
title: "ConverterSettings"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les paramètres pour personnaliser le comportement."
type: docs
weight: 11
url: /fr/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Définit les paramètres pour personnaliser le comportement de [Converter](../../com.groupdocs.conversion/converter).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCache()](#getCache--) | L'implémentation du cache utilisée pour stocker les résultats de conversion. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | L'implémentation du cache utilisée pour stocker les résultats de conversion. |
|
|  | [getLogger()](#getLogger--) | L'implémentation du journal utilisé pour consigner le processus de conversion. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | L'implémentation du journal utilisé pour consigner le processus de conversion. |
|
|  | [getListener()](#getListener--) | Obtient l'implémentation de l'écouteur du convertisseur utilisée pour surveiller l'état et la progression de la conversion. |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Définit l'implémentation de l'écouteur du convertisseur utilisée pour surveiller l'état et la progression de la conversion. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Les chemins des répertoires de polices personnalisées |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Les chemins des répertoires de polices personnalisées |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Dossier temporaire utilisé pour la conversion |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Définit le dossier temporaire utilisé pour la conversion |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


L'implémentation du cache utilisée pour stocker les résultats de conversion.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


L'implémentation du cache utilisée pour stocker les résultats de conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


L'implémentation du journal utilisé pour consigner le processus de conversion.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


L'implémentation du journal utilisé pour consigner le processus de conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Obtient l'implémentation de l'écouteur du convertisseur utilisée pour surveiller l'état et la progression de la conversion.


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Définit l'implémentation de l'écouteur du convertisseur utilisée pour surveiller l'état et la progression de la conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | L'écouteur du convertisseur |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Les chemins des répertoires de polices personnalisées


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


Les chemins des répertoires de polices personnalisées


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<java.lang.String> |  |

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


Dossier temporaire utilisé pour la conversion


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Définit le dossier temporaire utilisé pour la conversion


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

