---
title: "PresentationLoadOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры загрузки документов презентаций."
type: docs
weight: 29
url: /ru/java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IDocumentsContainerLoadOptions
```

Параметры загрузки документов презентаций.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PresentationLoadOptions()](#PresentationLoadOptions--) | Инициализирует новый экземпляр класса [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для рендеринга презентации. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для рендеринга презентации. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Заменять определённые шрифты при конвертации документа Presentation. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Заменять определённые шрифты при конвертации документа Presentation. |
|
|  | [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
|
|  | [getHideComments()](#getHideComments--) | Скрывать комментарии. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Скрывать комментарии. |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Показывать скрытые слайды. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Показывать скрытые слайды. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
|  | [getNotesPosition()](#getNotesPosition--) | Представляет способ печати комментариев вместе со слайдом. |
|
|  | [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | Представляет способ печати заметок вместе со слайдом. |
|
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


Инициализирует новый экземпляр класса [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


Тип файла входного документа.


**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для отображения презентации. Следующий шрифт будет использован, если шрифт презентации отсутствует.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для отображения презентации. Следующий шрифт будет использован, если шрифт презентации отсутствует.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Заменять определённые шрифты при конвертации документа Presentation.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Заменять определённые шрифты при конвертации документа Presentation.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Установить пароль для снятия защиты с защищённого документа.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установить пароль для снятия защиты с защищённого документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Скрывать комментарии.


**Returns:**
логический
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Скрывать комментарии.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Показывать скрытые слайды.


**Returns:**
логический
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Показывать скрытые слайды.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

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

### getDocumentFontSources() {#getDocumentFontSources--}
```
public List<String> getDocumentFontSources()
```




**Returns:**
java.util.List<java.lang.String>
### setDocumentFontSources(List<String> documentFontSources) {#setDocumentFontSources-java.util.List-java.lang.String--}
```
public void setDocumentFontSources(List<String> documentFontSources)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


Представляет способ печати комментариев вместе со слайдом. По умолчанию — None.


**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


Представляет способ печати заметок вместе со слайдом. По умолчанию — None.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| notesPosition | [PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition) |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public PresentationCommentsPosition getCommentsPosition()
```




**Returns:**
[PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) - 
### setCommentsPosition(PresentationCommentsPosition commentsPosition) {#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-}
```
public void setCommentsPosition(PresentationCommentsPosition commentsPosition)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

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

