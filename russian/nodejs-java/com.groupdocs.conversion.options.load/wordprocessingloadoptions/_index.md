---
title: "WordProcessingLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов WordProcessing."
type: docs
weight: 44
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Параметры загрузки документов WordProcessing.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Инициализирует новый экземпляр класса [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) class. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Шрифт по умолчанию для документа Words. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Шрифт по умолчанию для документа Words. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Заменять конкретные шрифты при конвертации документа Words. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Если EmbedTrueTypeFonts установлено в true, GroupDocs.Conversion внедряет шрифты TrueType в выходной документ. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | Обновлять макет страницы после загрузки. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | Обновлять поля после загрузки. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Сохранять оригинальное значение поля даты. |
| [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Устанавливает сохранение оригинального значения поля даты. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Заменять конкретные шрифты при конвертации документа Words. |
| [getPassword()](#getPassword--) | Установить пароль для снятия защиты с защищённого документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установить пароль для снятия защиты с защищённого документа. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Скрывать разметку и отслеживание изменений для документов Word. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Скрывать разметку и отслеживание изменений для документов Word. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Скрывать комментарии. |
| [getBookmarkOptions()](#getBookmarkOptions--) | Параметры закладок |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Параметры закладок |
| [isPreserveFontFields()](#isPreserveFontFields--) | Указывает, сохранять ли поля форм Microsoft Word как поля форм в PDF или преобразовывать их в текст. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Устанавливает флаг preserveFontFields |
| [isUseTextShaper()](#isUseTextShaper--) | Указывает, использовать ли текстовый шейпер для лучшего отображения кернинга. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Указывает, использовать ли текстовый шейпер для лучшего отображения кернинга. |
| [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Определяет, следует ли сохранять структуру документа при конвертации в PDF (по умолчанию false). |
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
| [getCommentDisplayMode()](#getCommentDisplayMode--) | Указывает, как комментарии должны отображаться в выходном документе. |
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
| [getShowFullCommenterName()](#getShowFullCommenterName--) | Отображать полное имя комментатора в комментариях. |
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Инициализирует новый экземпляр класса [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) class.

### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Тип файла входного документа

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


Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. Если AutoFontSubstitution включена, GroupDocs.Conversion оценивает все связанные поля в FontInfo (Panose, Sig и т.д.) для отсутствующего шрифта и находит наиболее подходящее совпадение среди доступных источников шрифтов. Обратите внимание, что механизм замены шрифтов переопределит DefaultFont в случаях, когда FontInfo для отсутствующего шрифта доступен в документе. Значение по умолчанию: True.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Если AutoFontSubstitution отключена, GroupDocs.Conversion использует DefaultFont для замены отсутствующих шрифтов. Если AutoFontSubstitution включена, GroupDocs.Conversion оценивает все связанные поля в FontInfo (Panose, Sig и т.д.) для отсутствующего шрифта и находит наиболее подходящее совпадение среди доступных источников шрифтов. Обратите внимание, что механизм замены шрифтов переопределит DefaultFont в случаях, когда FontInfo для отсутствующего шрифта доступен в документе. Значение по умолчанию: True.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


Если EmbedTrueTypeFonts равно true, GroupDocs.Conversion встраивает шрифты TrueType в выходной документ. По умолчанию: false.

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Обновлять макет страницы после загрузки. По умолчанию: false.

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Обновлять поля после загрузки. По умолчанию: false.

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Сохранять оригинальное значение поля даты. По умолчанию: false.

**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Устанавливает сохранение оригинального значения поля даты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

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
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Скрывать разметку и отслеживание изменений для документов Word.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Скрывать комментарии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


Указывает, следует ли сохранять поля формы Microsoft Word как поля формы в PDF или преобразовывать их в текст. По умолчанию: false.

**Returns:**
boolean — флаг preserveFontFields
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Устанавливает флаг preserveFontFields

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| preserveFontFields | boolean | сохранять поля формы Microsoft Word как поля формы в PDF или преобразовывать их в текст |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Указывает, следует ли использовать текстовый шейпер для лучшего отображения кернинга. По умолчанию: false.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Указывает, следует ли использовать текстовый шейпер для лучшего отображения кернинга. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isUseTextShaper | boolean | флаг isUseTextShaper |

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Определяет, следует ли сохранять структуру документа при конвертации в PDF (по умолчанию: false). Обратите внимание, что экспорт структуры документа значительно увеличивает потребление памяти, особенно для больших документов.

**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Если true, все внешние ресурсы не будут загружаться, за исключением ресурсов в

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| skip | boolean |  |

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


Указывает, как комментарии должны отображаться в выходном документе. По умолчанию: ShowInBalloons.

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


Отображать полное имя комментатора в комментариях. По умолчанию: false.

**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

