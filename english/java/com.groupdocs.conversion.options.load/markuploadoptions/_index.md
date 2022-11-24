---
title: MarkupLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Markup documents.
type: docs
weight: 19
url: /java/com.groupdocs.conversion.options.load/markuploadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public class MarkupLoadOptions extends LoadOptions implements Serializable
```

Options for loading Markup documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkupLoadOptions()](#MarkupLoadOptions--) | ctor |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [isPageNumbering()](#isPageNumbering--) | Enable or disable generation of page numbering in converted document. |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) | Sets page numbering |
| [getBasePath()](#getBasePath--) | Gets base path or URL |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) | Sets base path or URL |
| [getEncoding()](#getEncoding--) | Gets the encoding to be used when loading the markup document. |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) | Sets the encoding to be used when loading the markup document. |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Timeout for loading external resources |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) |  |
### MarkupLoadOptions() {#MarkupLoadOptions--}
```
public MarkupLoadOptions()
```


ctor

### getFormat() {#getFormat--}
```
public MarkupFileType getFormat()
```


Input document file type

**Returns:**
[MarkupFileType](../../com.groupdocs.conversion.filetypes/markupfiletype)
### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Enable or disable generation of page numbering in converted document. Default: false

**Returns:**
boolean - page numbering
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```


Sets page numbering

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumbering | boolean | page numbering flag |

### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


Gets base path or URL

**Returns:**
java.lang.String - base path or URL
### setBasePath(String basePath) {#setBasePath-java.lang.String-}
```
public void setBasePath(String basePath)
```


Sets base path or URL

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| basePath | java.lang.String | base path or URL |

### getEncoding() {#getEncoding--}
```
public String getEncoding()
```


Gets the encoding to be used when loading the markup document. If the property is null the encoding will be determined from document character set attribute

**Returns:**
java.lang.String - 
### setEncoding(String encoding) {#setEncoding-java.lang.String-}
```
public void setEncoding(String encoding)
```


Sets the encoding to be used when loading the markup document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | java.lang.String | encoding |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


Timeout for loading external resources

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

