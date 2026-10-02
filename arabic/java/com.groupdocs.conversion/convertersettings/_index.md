---
title: "ConverterSettings"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد الإعدادات لتخصيص السلوك."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

يحدد الإعدادات لتخصيص سلوك [Converter](../../com.groupdocs.conversion/converter).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCache()](#getCache--) | تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج التحويل. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج التحويل. |
|
|  | [getLogger()](#getLogger--) | تنفيذ المسجل المستخدم لتسجيل عملية التحويل. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | تنفيذ المسجل المستخدم لتسجيل عملية التحويل. |
|
|  | [getListener()](#getListener--) | يحصل على تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل وتقدمه |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | يضبط تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل وتقدمه |
|
|  | [getFontDirectories()](#getFontDirectories--) | مسارات دلائل الخطوط المخصصة |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | مسارات دلائل الخطوط المخصصة |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | المجلد المؤقت المستخدم للتحويل |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | يضبط المجلد المؤقت المستخدم للتحويل |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج التحويل.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


تنفيذ المسجل المستخدم لتسجيل عملية التحويل.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


تنفيذ المسجل المستخدم لتسجيل عملية التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


يحصل على تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل وتقدمه


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


يضبط تنفيذ مستمع المحول المستخدم لمراقبة حالة التحويل وتقدمه


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | مستمع المحول |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


مسارات دلائل الخطوط المخصصة


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


مسارات دلائل الخطوط المخصصة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<java.lang.String> |  |

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


المجلد المؤقت المستخدم للتحويل


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


يضبط المجلد المؤقت المستخدم للتحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

