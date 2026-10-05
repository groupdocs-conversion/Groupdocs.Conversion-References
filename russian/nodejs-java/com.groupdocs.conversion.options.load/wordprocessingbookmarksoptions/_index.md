---
title: "WordProcessingBookmarksOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры обработки закладок в WordProcessing"
type: docs
weight: 43
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Параметры обработки закладок в WordProcessing
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Указывает уровень по умолчанию в структуре документа, на котором отображать закладки Word. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Указывает уровень по умолчанию в структуре документа, на котором отображать закладки Word. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Указывает, сколько уровней заголовков (абзацев, отформатированных стилями Heading) включать в структуру документа. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Указывает, сколько уровней заголовков (абзацев, отформатированных стилями Heading) включать в структуру документа. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре файла. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре файла. |
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Указывает уровень по умолчанию в структуре документа, на котором отображать закладки Word. По умолчанию 0. Допустимый диапазон от 0 до 9.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Указывает уровень по умолчанию в структуре документа, на котором отображать закладки Word. По умолчанию 0. Допустимый диапазон от 0 до 9.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Указывает, сколько уровней заголовков (абзацев, отформатированных стилями Heading) включать в структуру документа. По умолчанию 0. Допустимый диапазон от 0 до 9.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Указывает, сколько уровней заголовков (абзацев, отформатированных стилями Heading) включать в структуру документа. По умолчанию 0. Допустимый диапазон от 0 до 9.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре файла. По умолчанию 0. Допустимый диапазон от 0 до 9. Обратите внимание, что эта опция не будет работать при сохранении в XPS.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре файла. По умолчанию 0. Допустимый диапазон от 0 до 9. Обратите внимание, что эта опция не будет работать при сохранении в XPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

