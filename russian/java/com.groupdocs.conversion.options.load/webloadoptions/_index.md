---
title: "WebLoadOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры загрузки веб-документов."
type: docs
weight: 38
url: /ru/java/com.groupdocs.conversion.options.load/webloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions)
```
public class WebLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions
```

Параметры загрузки веб-документов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WebLoadOptions()](#WebLoadOptions--) | Инициализирует новый экземпляр класса. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Получает тип файла входного документа. |
|
|  | [setFormat(WebFileType format)](#setFormat-com.groupdocs.conversion.filetypes.WebFileType-) | Устанавливает тип файла входного документа. |
|
| [isPageNumbering()](#isPageNumbering--) |  |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) |  |
| [getBasePath()](#getBasePath--) |  |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) |  |
| [getEncoding()](#getEncoding--) |  |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Получает тайм-аут загрузки внешних ресурсов в миллисекундах |
|
|  | [setResourceLoadingTimeout(long resourceLoadingTimeout)](#setResourceLoadingTimeout-long-) | Устанавливает тайм-аут загрузки внешних ресурсов в миллисекундах |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [isUsePdf()](#isUsePdf--) | Использовать pdf для конвертации. |
|
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
### WebLoadOptions() {#WebLoadOptions--}
```
public WebLoadOptions()
```


Инициализирует новый экземпляр класса.


### getFormat() {#getFormat--}
```
public WebFileType getFormat()
```


Получает тип файла входного документа.


**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
### setFormat(WebFileType format) {#setFormat-com.groupdocs.conversion.filetypes.WebFileType-}
```
public void setFormat(WebFileType format)
```


Устанавливает тип файла входного документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype) |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Включить или отключить генерацию нумерации страниц в конвертированном документе. По умолчанию: false


**Returns:**
логический
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumbering | логический |  |

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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| кодировка | java.lang.String |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public long getResourceLoadingTimeout()
```


Получает тайм-аут загрузки внешних ресурсов в миллисекундах


**Returns:**
long
### setResourceLoadingTimeout(long resourceLoadingTimeout) {#setResourceLoadingTimeout-long-}
```
public void setResourceLoadingTimeout(long resourceLoadingTimeout)
```


Устанавливает тайм-аут загрузки внешних ресурсов в миллисекундах


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceLoadingTimeout | long |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Если true, все внешние ресурсы не будут загружаться, за исключением ресурсов в


**Returns:**
логический
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| skip | логический |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Внешние ресурсы, которые всегда будут загружаться


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```


Использовать pdf для конвертации. По умолчанию: false


**Returns:**
логический
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| usePdf | логический |  |

