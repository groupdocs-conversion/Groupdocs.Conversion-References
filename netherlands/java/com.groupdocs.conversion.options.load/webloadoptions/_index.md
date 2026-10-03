---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van web‑documenten."
type: docs
weight: 38
url: /nl/java/com.groupdocs.conversion.options.load/webloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions)
```
public class WebLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions
```

Opties voor het laden van web‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WebLoadOptions()](#WebLoadOptions--) | Initialiseert een nieuwe instantie van de klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Verkrijgt het bestandstype van het invoerdocument. |
|
|  | [setFormat(WebFileType format)](#setFormat-com.groupdocs.conversion.filetypes.WebFileType-) | Stelt het bestandstype van het invoerdocument in. |
|
| [isPageNumbering()](#isPageNumbering--) |  |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) |  |
| [getBasePath()](#getBasePath--) |  |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) |  |
| [getEncoding()](#getEncoding--) |  |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Haalt time-out op voor het laden van externe bronnen in milliseconden |
|
|  | [setResourceLoadingTimeout(long resourceLoadingTimeout)](#setResourceLoadingTimeout-long-) | Stelt time-out in voor het laden van externe bronnen in milliseconden |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [isUsePdf()](#isUsePdf--) | Gebruik pdf voor de conversie. |
|
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
### WebLoadOptions() {#WebLoadOptions--}
```
public WebLoadOptions()
```


Initialiseert een nieuwe instantie van de klasse.


### getFormat() {#getFormat--}
```
public WebFileType getFormat()
```


Verkrijgt het bestandstype van het invoerdocument.


**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
### setFormat(WebFileType format) {#setFormat-com.groupdocs.conversion.filetypes.WebFileType-}
```
public void setFormat(WebFileType format)
```


Stelt het bestandstype van het invoerdocument in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype) |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Inschakelen of uitschakelen van het genereren van paginanummering in het geconverteerde document. Standaard: false


**Returns:**
boolean
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encoding | java.lang.String |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public long getResourceLoadingTimeout()
```


Haalt time-out op voor het laden van externe bronnen in milliseconden


**Returns:**
long
### setResourceLoadingTimeout(long resourceLoadingTimeout) {#setResourceLoadingTimeout-long-}
```
public void setResourceLoadingTimeout(long resourceLoadingTimeout)
```


Stelt time-out in voor het laden van externe bronnen in milliseconden


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceLoadingTimeout | long |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Als true worden alle externe bronnen niet geladen, met uitzondering van de bronnen in de


**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| overslaan | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Externe bronnen die altijd worden geladen


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```


Gebruik pdf voor de conversie. Standaard: false


**Returns:**
boolean
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| usePdf | boolean |  |

