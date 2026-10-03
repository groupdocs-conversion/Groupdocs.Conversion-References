---
title: "EmailLoadOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры загрузки документов электронной почты."
type: docs
weight: 18
url: /ru/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Параметры загрузки документов электронной почты.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Инициализирует новый экземпляр класса [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Опция отображения или скрытия заголовка письма. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Опция отображения или скрытия заголовка письма. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Опция отображения или скрытия адреса "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Опция отображения или скрытия адреса "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Опция отображения или скрытия адреса "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Опция отображения или скрытия адреса "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Опция отображения или скрытия адреса "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Опция отображения или скрытия адреса "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Опция отображения или скрытия адреса "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Опция отображения или скрытия адреса "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Тайм-аут загрузки внешних ресурсов |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Тайм-аут загрузки внешних ресурсов (установщик) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Получает или задает смещение координированного всемирного времени (UTC) для дат сообщений. |
|
|  | [deepClone()](#deepClone--) | Клонирует текущий экземпляр. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Получает сопоставление между электронным сообщением и текстовым представлением поля |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Задает сопоставление между электронным сообщением и текстовым представлением поля |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Определяет, нужно ли сохранять оригинальную строку заголовка даты в письме при сохранении (значение по умолчанию: true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Определяет, нужно ли сохранять оригинальную строку заголовка даты в письме при сохранении |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Получает опцию отображения или скрытия вложений в заголовке. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Задает опцию отображения или скрытия вложений в заголовке. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Получает опцию отображения или скрытия темы в заголовке. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Задает опцию отображения или скрытия темы в заголовке |
|
|  | [isDisplaySent()](#isDisplaySent--) | Получает опцию отображения или скрытия даты/времени отправки в заголовке. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Задает опцию отображения или скрытия даты/времени отправки в заголовке. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Пропускает загрузку http-ресурсов, если true |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Инициализирует новый экземпляр класса [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Тип файла входного документа.


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Опция отображения или скрытия заголовка email. По умолчанию: true.


**Returns:**
логический
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Опция отображения или скрытия заголовка email. По умолчанию: true.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Опция отображения или скрытия адреса email "from". По умолчанию: true.


**Returns:**
логический
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Опция отображения или скрытия адреса email "from". По умолчанию: true.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Опция отображения или скрытия адреса email "to". По умолчанию: true.


**Returns:**
логический
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Опция отображения или скрытия адреса email "to". По умолчанию: true.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Опция отображения или скрытия адреса email "Cc". По умолчанию: false.


**Returns:**
логический
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Опция отображения или скрытия адреса email "Cc". По умолчанию: false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Опция отображения или скрытия адреса email "Bcc". По умолчанию: false.


**Returns:**
логический
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Опция отображения или скрытия адреса email "Bcc". По умолчанию: false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

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


Получает сопоставление между электронным сообщением и текстовым представлением поля


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - отображение

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Задает сопоставление между электронным сообщением и текстовым представлением поля


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | отображение |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Определяет, нужно ли сохранять оригинальную строку заголовка даты в письме при сохранении (значение по умолчанию: true)


**Returns:**
boolean - сохраняет оригинальную дату, если true

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Определяет, нужно ли сохранять оригинальную строку заголовка даты в письме при сохранении


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | preserveOriginalDate | логический | сохранять оригинальную дату |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Получает параметр, позволяющий контролировать, должен ли контейнер документов сам быть конвертирован


**Returns:**
логический
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOwner | логический |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Опция для управления тем, должны ли принадлежащие документы в контейнере документов быть преобразованы


**Returns:**
логический
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOwned | логический |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Опция для управления тем, сколько уровней глубины использовать при выполнении преобразования


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Получает опцию отображения или скрытия вложений в заголовке. По умолчанию: true.


**Returns:**
логический
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Задает опцию отображения или скрытия вложений в заголовке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| displayAttachments | логический |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Получает опцию отображения или скрытия темы в заголовке. По умолчанию: true.


**Returns:**
логический
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Задает опцию отображения или скрытия темы в заголовке


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| displaySubject | логический |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Получает опцию отображения или скрытия даты/времени отправки в заголовке. По умолчанию: true.


**Returns:**
логический
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Задает опцию отображения или скрытия даты/времени отправки в заголовке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| displaySent | логический |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Пропускает загрузку http-ресурсов, если true


**Returns:**
логический
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| skipExternalResources | логический |  |

