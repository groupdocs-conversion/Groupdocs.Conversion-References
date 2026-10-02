---
title: "ConverterSettings"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义用于自定义行为的设置。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

定义用于自定义 [Converter](../../com.groupdocs.conversion/converter) 行为的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCache()](#getCache--) | 用于存储转换结果的缓存实现。 |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | 用于存储转换结果的缓存实现。 |
|
|  | [getLogger()](#getLogger--) | 用于记录转换过程的日志实现。 |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | 用于记录转换过程的日志实现。 |
|
|  | [getListener()](#getListener--) | 获取用于监控转换状态和进度的转换器监听器实现 |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | 设置用于监控转换状态和进度的转换器监听器实现 |
|
|  | [getFontDirectories()](#getFontDirectories--) | 自定义字体目录路径 |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | 自定义字体目录路径 |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | 用于转换的临时文件夹 |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | 设置用于转换的临时文件夹 |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


用于存储转换结果的缓存实现。


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


用于存储转换结果的缓存实现。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


用于记录转换过程的日志实现。


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


用于记录转换过程的日志实现。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


获取用于监控转换状态和进度的转换器监听器实现


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


设置用于监控转换状态和进度的转换器监听器实现


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | 转换器监听器 |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


自定义字体目录路径


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


自定义字体目录路径


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<java.lang.String> |  |

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


用于转换的临时文件夹


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


设置用于转换的临时文件夹


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

