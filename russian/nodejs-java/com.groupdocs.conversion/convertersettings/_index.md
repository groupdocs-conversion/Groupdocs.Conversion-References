---
title: "ConverterSettings"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет настройки для настройки поведения."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Определяет настройки для настройки поведения [Converter](../../com.groupdocs.conversion/converter).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCache()](#getCache--) | Реализация кэша, используемая для хранения результатов конвертации. |
| [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | Реализация кэша, используемая для хранения результатов конвертации. |
| [getLogger()](#getLogger--) | Реализация логгера, используемая для регистрации процесса конвертации. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | Реализация логгера, используемая для регистрации процесса конвертации. |
| [getListener()](#getListener--) | Получает реализацию слушателя конвертера, используемую для мониторинга статуса и прогресса конвертации. |
| [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Устанавливает реализацию слушателя конвертера, используемую для мониторинга статуса и прогресса конвертации. |
| [getFontDirectories()](#getFontDirectories--) | Пути к пользовательским каталогам шрифтов |
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
| [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Пути к пользовательским каталогам шрифтов |
| [listConverterSettings()](#listConverterSettings--) |  |
| [getTempFolder()](#getTempFolder--) | Временная папка, используемая для конвертации |
| [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Устанавливает временную папку, используемую для конвертации |
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Реализация кэша, используемая для хранения результатов конвертации.

**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


Реализация кэша, используемая для хранения результатов конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Реализация логгера, используемая для регистрации процесса конвертации.

**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Реализация логгера, используемая для регистрации процесса конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Получает реализацию слушателя конвертера, используемую для мониторинга статуса и прогресса конвертации.

**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener
### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Устанавливает реализацию слушателя конвертера, используемую для мониторинга статуса и прогресса конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Слушатель конвертера |

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Пути к пользовательским каталогам шрифтов

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


Пути к пользовательским каталогам шрифтов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<java.lang.String> |  |

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


Временная папка, используемая для конвертации

**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Устанавливает временную папку, используемую для конвертации

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

