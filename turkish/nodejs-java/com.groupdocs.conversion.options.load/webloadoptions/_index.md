---
title: "WebLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Web belgelerini yükleme seçenekleri."
type: docs
weight: 42
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/webloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WebLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Web belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebLoadOptions()](#WebLoadOptions--) | class'ın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) | Giriş belge dosya türünü alır. |
| [setFormat(WebFileType format)](#setFormat-com.groupdocs.conversion.filetypes.WebFileType-) | Giriş belge dosya türünü ayarlar. |
| [isPageNumbering()](#isPageNumbering--) |  |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) |  |
| [getBasePath()](#getBasePath--) |  |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) |  |
| [getEncoding()](#getEncoding--) |  |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) |  |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
### WebLoadOptions() {#WebLoadOptions--}
```
public WebLoadOptions()
```


class'ın yeni bir örneğini başlatır.

### getFormat() {#getFormat--}
```
public WebFileType getFormat()
```


Giriş belge dosya türünü alır.

**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
### setFormat(WebFileType format) {#setFormat-com.groupdocs.conversion.filetypes.WebFileType-}
```
public void setFormat(WebFileType format)
```


Giriş belge dosya türünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype) |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```




**Returns:**
boolean
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kodlama | java.lang.String |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Eğer true ise, tüm harici kaynaklar, içinde bulunan kaynaklar hariç, yüklenmeyecek.

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Her zaman yüklenecek harici kaynaklar

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

