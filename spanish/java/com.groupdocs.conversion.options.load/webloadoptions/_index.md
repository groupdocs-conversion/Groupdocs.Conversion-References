---
title: "WebLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos web."
type: docs
weight: 38
url: /es/java/com.groupdocs.conversion.options.load/webloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions)
```
public class WebLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions
```

Opciones para cargar documentos web.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WebLoadOptions()](#WebLoadOptions--) | Inicializa una nueva instancia de la clase. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Obtiene el tipo de archivo del documento de entrada. |
|
|  | [setFormat(WebFileType format)](#setFormat-com.groupdocs.conversion.filetypes.WebFileType-) | Establece el tipo de archivo del documento de entrada. |
|
| [isPageNumbering()](#isPageNumbering--) |  |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) |  |
| [getBasePath()](#getBasePath--) |  |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) |  |
| [getEncoding()](#getEncoding--) |  |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Obtiene el tiempo de espera para cargar recursos externos en milisegundos |
|
|  | [setResourceLoadingTimeout(long resourceLoadingTimeout)](#setResourceLoadingTimeout-long-) | Establece el tiempo de espera para cargar recursos externos en milisegundos |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [isUsePdf()](#isUsePdf--) | Usar pdf para la conversión. |
|
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
### WebLoadOptions() {#WebLoadOptions--}
```
public WebLoadOptions()
```


Inicializa una nueva instancia de la clase.


### getFormat() {#getFormat--}
```
public WebFileType getFormat()
```


Obtiene el tipo de archivo del documento de entrada.


**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
### setFormat(WebFileType format) {#setFormat-com.groupdocs.conversion.filetypes.WebFileType-}
```
public void setFormat(WebFileType format)
```


Establece el tipo de archivo del documento de entrada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype) |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Habilitar o deshabilitar la generación de numeración de páginas en el documento convertido. Predeterminado: false


**Returns:**
booleano
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumbering | booleano |  |

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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codificación | java.lang.String |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public long getResourceLoadingTimeout()
```


Obtiene el tiempo de espera para cargar recursos externos en milisegundos


**Returns:**
long
### setResourceLoadingTimeout(long resourceLoadingTimeout) {#setResourceLoadingTimeout-long-}
```
public void setResourceLoadingTimeout(long resourceLoadingTimeout)
```


Establece el tiempo de espera para cargar recursos externos en milisegundos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceLoadingTimeout | long |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Si es true, todos los recursos externos no se cargarán, con excepción de los recursos en el


**Returns:**
booleano
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| omitir | booleano |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Recursos externos que siempre se cargarán


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```


Usar pdf para la conversión. Predeterminado: false


**Returns:**
booleano
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| usePdf | booleano |  |

