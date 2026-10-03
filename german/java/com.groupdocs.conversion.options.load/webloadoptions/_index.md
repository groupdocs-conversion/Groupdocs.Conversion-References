---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Webdokumenten."
type: docs
weight: 38
url: /de/java/com.groupdocs.conversion.options.load/webloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions)
```
public class WebLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions
```

Optionen zum Laden von Webdokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WebLoadOptions()](#WebLoadOptions--) | Initialisiert eine neue Instanz der Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Liest den Dateityp des Eingabedokuments. |
|
|  | [setFormat(WebFileType format)](#setFormat-com.groupdocs.conversion.filetypes.WebFileType-) | Setzt den Dateityp des Eingabedokuments. |
|
| [isPageNumbering()](#isPageNumbering--) |  |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) |  |
| [getBasePath()](#getBasePath--) |  |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) |  |
| [getEncoding()](#getEncoding--) |  |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Ermittelt Timeout für das Laden externer Ressourcen in Millisekunden |
|
|  | [setResourceLoadingTimeout(long resourceLoadingTimeout)](#setResourceLoadingTimeout-long-) | Setzt Timeout für das Laden externer Ressourcen in Millisekunden |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [isUsePdf()](#isUsePdf--) | Verwende PDF für die Konvertierung. |
|
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
### WebLoadOptions() {#WebLoadOptions--}
```
public WebLoadOptions()
```


Initialisiert eine neue Instanz der Klasse.


### getFormat() {#getFormat--}
```
public WebFileType getFormat()
```


Liest den Dateityp des Eingabedokuments.


**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
### setFormat(WebFileType format) {#setFormat-com.groupdocs.conversion.filetypes.WebFileType-}
```
public void setFormat(WebFileType format)
```


Setzt den Dateityp des Eingabedokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype) |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Aktivieren oder deaktivieren der Seitennummerierung im konvertierten Dokument. Standard: false


**Returns:**
boolean
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumbering | boolean |  |

### getBasePath() {#getBasePath--}
```
public String getBasePath()
```




**Returns:**
java.lang.String
### setBasePath(String basePath) {#setBasePath-java.lang.String-}
```
public void setBasePath(String basePath)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| basePath | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public String getEncoding()
```




**Returns:**
java.lang.String
### setEncoding(String encoding) {#setEncoding-java.lang.String-}
```
public void setEncoding(String encoding)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kodierung | java.lang.String |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public long getResourceLoadingTimeout()
```


Ermittelt Timeout für das Laden externer Ressourcen in Millisekunden


**Returns:**
long
### setResourceLoadingTimeout(long resourceLoadingTimeout) {#setResourceLoadingTimeout-long-}
```
public void setResourceLoadingTimeout(long resourceLoadingTimeout)
```


Setzt Timeout für das Laden externer Ressourcen in Millisekunden


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceLoadingTimeout | long |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Wenn true, werden alle externen Ressourcen nicht geladen, mit Ausnahme der Ressourcen in der


**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Externe Ressourcen, die immer geladen werden


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```


Verwende PDF für die Konvertierung. Standard: false


**Returns:**
boolean
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| usePdf | boolean |  |

