---
title: "WordProcessingLoadOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры загрузки документов WordProcessing."
type: docs
weight: 40
url: /ru/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Параметры загрузки документов WordProcessing.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Инициализирует новый экземпляр класса [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для документа Words. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для документа Words. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Заменять конкретные шрифты при конвертации документа Words. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Если EmbedTrueTypeFonts истинно, GroupDocs.Conversion встраивает TrueType-шрифты в выходной документ. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Обновлять макет страницы после загрузки. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Обновлять поля после загрузки. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Сохранять оригинальное значение поля даты. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Устанавливает сохранение оригинального значения поля даты. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Заменять конкретные шрифты при конвертации документа Words. |
|
|  | [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Скрывать разметку и отслеживание изменений для документов Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Скрывать разметку и отслеживание изменений для документов Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Скрывать комментарии. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Параметры закладок |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Параметры закладок |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Указывает, сохранять ли поля форм Microsoft Word как поля форм в PDF или преобразовывать их в текст. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Устанавливает флаг preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Указывает, использовать ли текстовый шейпер для лучшего отображения кернинга. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Указывает, использовать ли текстовый шейпер для лучшего отображения кернинга. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Определяет, следует ли сохранять структуру документа при конвертации в PDF (по умолчанию false). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Указывает, как комментарии должны отображаться в выходном документе. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Отображать полное имя комментатора в комментариях. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Включить или отключить генерацию нумерации страниц в конвертированном документе. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Получает параметры переноса слов для документов WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Устанавливает параметры переноса слов для документов WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Получает флаг InterruptThreadIfImageExceptionThrown. По умолчанию: false. Если true, то прерывает основной поток конвертации при возникновении исключения в потоке обработки изображения. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Устанавливает флаг InterruptThreadIfImageExceptionThrown. |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Когда включено (по умолчанию), абзацы и участки текста, где доминирует направление справа налево (RTL), будут иметь исправленные bidi‑флаги перед конвертацией. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Устанавливает параметр autoDetectRtlDirection. |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Инициализирует новый экземпляр класса [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Тип файла входного документа.


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Шрифт по умолчанию для документа Words. Следующий шрифт будет использован, если шрифт отсутствует.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Шрифт по умолчанию для документа Words. Следующий шрифт будет использован, если шрифт отсутствует.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. Если AutoFontSubstitution включена,
GroupDocs.Conversion оценивает все связанные поля в FontInfo (Panose, Sig и др.) для отсутствующего шрифта и находит наиболее подходящее совпадение среди доступных источников шрифтов.
Обратите внимание, что механизм замены шрифтов переопределит DefaultFont в случаях, когда FontInfo для отсутствующего шрифта доступен в документе. Значение по умолчанию — True.


**Returns:**
логический
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. Если AutoFontSubstitution включена,
GroupDocs.Conversion оценивает все связанные поля в FontInfo (Panose, Sig и др.) для отсутствующего шрифта и находит наиболее подходящее совпадение среди доступных источников шрифтов.
Обратите внимание, что механизм замены шрифтов переопределит DefaultFont в случаях, когда FontInfo для отсутствующего шрифта доступен в документе. Значение по умолчанию — True.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Заменять конкретные шрифты при конвертации документа Words.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Если EmbedTrueTypeFonts равно true, GroupDocs.Conversion встраивает TrueType‑шрифты в выходной документ. По умолчанию: false.


**Returns:**
логический
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embedTrueTypeFonts | логический |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Обновить макет страницы после загрузки. По умолчанию: false.


**Returns:**
логический
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| updatePageLayout | логический |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Обновить поля после загрузки. По умолчанию: false.


**Returns:**
логический
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| updateFields | логический |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Сохранить оригинальное значение поля даты. По умолчанию: false.


**Returns:**
логический
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Устанавливает сохранение оригинального значения поля даты.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keepDateFieldOriginalValue | логический |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Заменять конкретные шрифты при конвертации документа Words.


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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Скрывать разметку и отслеживание изменений для документов Word.


**Returns:**
логический
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Скрывать разметку и отслеживание изменений для документов Word.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Скрывать комментарии.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | логический |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Параметры закладок


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Параметры закладок


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Указывает, сохранять ли поля форм Microsoft Word как поля форм в PDF или конвертировать их в текст. По умолчанию — false.


**Returns:**
boolean — флаг preserveFontFields.

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Устанавливает флаг preserveFontFields


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | preserveFontFields | логический | сохранять поля форм Microsoft Word как поля форм в PDF или конвертировать их в текст |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Указывает, использовать ли текстовый шейпер для лучшего отображения кернинга. По умолчанию — false.


**Returns:**
логический
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Указывает, использовать ли текстовый шейпер для лучшего отображения кернинга. По умолчанию — false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | isUseTextShaper | логический | флаг isUseTextShaper |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Определяет, следует ли сохранять структуру документа при конвертации в PDF (по умолчанию false). Обратите внимание, что экспорт структуры документа значительно увеличивает потребление памяти, особенно для больших документов.


**Returns:**
логический
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| preserveDocumentStructure | логический |  |

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

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Указывает, как комментарии должны отображаться в выходном документе. По умолчанию ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Показывать полное имя комментатора в комментариях. По умолчанию false.


**Returns:**
логический
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| showFullCommenterName | логический |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Включить или отключить генерацию нумерации страниц в конвертированном документе. По умолчанию: false


**Returns:**
логический
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isPageNumbering | логический |  |

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Получает параметры переноса слов для документов WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Устанавливает параметры переноса слов для документов WordProcessing.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Получает флаг InterruptThreadIfImageExceptionThrown. По умолчанию: false. Если true, то прерывает основной поток конвертации при возникновении исключения в потоке обработки изображения.


**Returns:**
логический
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Устанавливает флаг InterruptThreadIfImageExceptionThrown.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | логический |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Когда включено (по умолчанию), абзацы и участки текста, где доминирует направление справа налево (RTL), будут иметь исправленные bidi‑флаги перед конвертацией.


Это соответствует эвристике, применяемой Microsoft Word и LibreOffice, и
исправляет рендеринг арабских/ивритских документов, созданных генераторами
(в частности Google Docs), которые генерируют OOXML без


и с

в последовательностях, содержащих только RTL-скрипт.


Установить в
false
для сохранения строгой интерпретации OOXML
исходной разметки.


**Returns:**
логический
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Устанавливает параметр autoDetectRtlDirection.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | autoDetectRtlDirection | логический | autoDetectRtlDirection |
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

