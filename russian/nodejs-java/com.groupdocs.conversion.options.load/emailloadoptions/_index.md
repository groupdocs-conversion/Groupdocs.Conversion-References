---
title: "EmailLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Email."
type: docs
weight: 19
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Параметры загрузки документов Email.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmailLoadOptions()](#EmailLoadOptions--) | Инициализирует новый экземпляр класса [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDisplayHeader()](#getDisplayHeader--) | Опция отображения или скрытия заголовка письма. |
| [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Опция отображения или скрытия заголовка письма. |
| [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Опция отображения или скрытия адреса электронной почты \"from\". |
| [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Опция отображения или скрытия адреса электронной почты \"from\". |
| [getDisplayEmailAddress()](#getDisplayEmailAddress--) | Опция отображения или скрытия адреса электронной почты. |
| [setDisplayEmailAddress(boolean value)](#setDisplayEmailAddress-boolean-) | Опция отображения или скрытия адреса электронной почты. |
| [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Опция отображения или скрытия адреса электронной почты \"to\". |
| [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Опция отображения или скрытия адреса электронной почты \"to\". |
| [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Опция отображения или скрытия адреса электронной почты \"Cc\". |
| [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Опция отображения или скрытия адреса электронной почты \"Cc\". |
| [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Опция отображения или скрытия адреса электронной почты \"Bcc\". |
| [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Опция отображения или скрытия адреса электронной почты \"Bcc\". |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. |
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Тайм-аут загрузки внешних ресурсов |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Тайм-аут загрузки внешних ресурсов (установщик) |
| [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. |
| [deepClone()](#deepClone--) | Клонирует текущий экземпляр. |
| [getFieldTextMap()](#getFieldTextMap--) | Получает сопоставление между сообщением электронной почты  и текстовым представлением поля |
| [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Устанавливает сопоставление между сообщением электронной почты  и текстовым представлением поля |
| [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Определяет, нужно ли сохранять оригинальную строку заголовка даты в сообщении электронной почты при сохранении или нет (значение по умолчанию — true) |
| [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Определяет, нужно ли сохранять оригинальную строку заголовка даты в сообщении электронной почты при сохранении или нет (значение по умолчанию — true) |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Инициализирует новый экземпляр класса [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).

### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Тип файла входного документа

**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Опция отображения или скрытия заголовка письма. По умолчанию: true.

**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Опция отображения или скрытия заголовка письма. По умолчанию: true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Опция отображения или скрытия "from" адреса электронной почты. По умолчанию: true.

**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Опция отображения или скрытия "from" адреса электронной почты. По умолчанию: true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDisplayEmailAddress() {#getDisplayEmailAddress--}
```
public final boolean getDisplayEmailAddress()
```


Опция отображения или скрытия адреса электронной почты. По умолчанию: true.

**Returns:**
boolean
### setDisplayEmailAddress(boolean value) {#setDisplayEmailAddress-boolean-}
```
public final void setDisplayEmailAddress(boolean value)
```


Опция отображения или скрытия адреса электронной почты. По умолчанию: true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Опция отображения или скрытия "to" адреса электронной почты. По умолчанию: true.

**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Опция отображения или скрытия "to" адреса электронной почты. По умолчанию: true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Опция отображения или скрытия "Cc" адреса электронной почты. По умолчанию: false.

**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Опция отображения или скрытия "Cc" адреса электронной почты. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Опция отображения или скрытия "Bcc" адреса электронной почты. По умолчанию: false.

**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Опция отображения или скрытия "Bcc" адреса электронной почты. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. Это свойство определяет разницу часового пояса между локальным временем и UTC.

**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


Тайм-аут загрузки внешних ресурсов

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Тайм-аут загрузки внешних ресурсов (установщик)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. Это свойство определяет разницу часового пояса между локальным временем и UTC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Клонирует текущий экземпляр.

**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Получает сопоставление между сообщением электронной почты  и текстовым представлением поля

**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - отображение
### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Устанавливает сопоставление между сообщением электронной почты  и текстовым представлением поля

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | отображение |

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Определяет, нужно ли сохранять оригинальную строку заголовка даты в сообщении электронной почты при сохранении или нет (значение по умолчанию — true)

**Returns:**
boolean - сохранять оригинальную дату, если true
### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Определяет, нужно ли сохранять оригинальную строку заголовка даты в сообщении электронной почты при сохранении или нет (значение по умолчанию — true)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| preserveOriginalDate | boolean | сохранить оригинальную дату |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Получает опцию, контролирующую, должен ли контейнер документов быть преобразован

**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Параметр, контролирующий, должны ли принадлежащие документы в контейнере документов быть преобразованы

**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Параметр, позволяющий контролировать, на сколько уровней глубины выполнять преобразование

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| глубина | int |  |

