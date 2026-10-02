---
title: "WebLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات الويب."
type: docs
weight: 38
url: /ar/java/com.groupdocs.conversion.options.load/webloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions)
```
public class WebLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions
```

خيارات تحميل مستندات الويب.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WebLoadOptions()](#WebLoadOptions--) | يقوم بإنشاء مثيل جديد للفئة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يحصل على نوع ملف المستند الإدخالي. |
|
|  | [setFormat(WebFileType format)](#setFormat-com.groupdocs.conversion.filetypes.WebFileType-) | يضبط نوع ملف المستند الإدخالي. |
|
| [isPageNumbering()](#isPageNumbering--) |  |
| [setPageNumbering(boolean pageNumbering)](#setPageNumbering-boolean-) |  |
| [getBasePath()](#getBasePath--) |  |
| [setBasePath(String basePath)](#setBasePath-java.lang.String-) |  |
| [getEncoding()](#getEncoding--) |  |
| [setEncoding(String encoding)](#setEncoding-java.lang.String-) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | يحصل على مهلة تحميل الموارد الخارجية بالملليثانية |
|
|  | [setResourceLoadingTimeout(long resourceLoadingTimeout)](#setResourceLoadingTimeout-long-) | يضبط مهلة تحميل الموارد الخارجية بالملليثانية |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [isUsePdf()](#isUsePdf--) | استخدم pdf للتحويل. |
|
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
### WebLoadOptions() {#WebLoadOptions--}
```
public WebLoadOptions()
```


يقوم بإنشاء مثيل جديد للفئة.


### getFormat() {#getFormat--}
```
public WebFileType getFormat()
```


يحصل على نوع ملف المستند الإدخالي.


**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
### setFormat(WebFileType format) {#setFormat-com.groupdocs.conversion.filetypes.WebFileType-}
```
public void setFormat(WebFileType format)
```


يضبط نوع ملف المستند الإدخالي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype) |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


تمكين أو تعطيل إنشاء ترقيم الصفحات في المستند المحول. الافتراضي: false


**Returns:**
منطقي
### setPageNumbering(boolean pageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean pageNumbering)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumbering | منطقي |  |

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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الترميز | java.lang.String |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public long getResourceLoadingTimeout()
```


يحصل على مهلة تحميل الموارد الخارجية بالملليثانية


**Returns:**
long
### setResourceLoadingTimeout(long resourceLoadingTimeout) {#setResourceLoadingTimeout-long-}
```
public void setResourceLoadingTimeout(long resourceLoadingTimeout)
```


يضبط مهلة تحميل الموارد الخارجية بالملليثانية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceLoadingTimeout | long |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


إذا كانت true لن يتم تحميل جميع الموارد الخارجية باستثناء الموارد الموجودة في الـ


**Returns:**
منطقي
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تخطي | منطقي |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


الموارد الخارجية التي سيتم تحميلها دائمًا


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```


استخدم pdf للتحويل. الافتراضي: false


**Returns:**
منطقي
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| usePdf | منطقي |  |

