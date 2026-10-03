---
title: "WordProcessingBookmarksOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "WordProcessing içinde yer imlerini işleme seçenekleri"
type: docs
weight: 39
url: /tr/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

WordProcessing içinde yer imlerini işleme seçenekleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Word yer imlerini gösterecek belge taslağındaki varsayılan seviyeyi belirtir. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Word yer imlerini gösterecek belge taslağındaki varsayılan seviyeyi belirtir. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Belge taslağında (Başlık stilleriyle biçimlendirilmiş paragraflar) kaç seviye başlık dahil edileceğini belirtir. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Belge taslağında (Başlık stilleriyle biçimlendirilmiş paragraflar) kaç seviye başlık dahil edileceğini belirtir. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Dosya görüntülendiğinde belge taslağında kaç seviye genişletilmiş gösterileceğini belirtir. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Dosya görüntülendiğinde belge taslağında kaç seviye genişletilmiş gösterileceğini belirtir. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Belge taslağında Word yer imlerinin gösterileceği varsayılan seviyeyi belirtir. Varsayılan değer 0'dır. Geçerli aralık 0 ile 9 arasındadır.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Belge taslağında Word yer imlerinin gösterileceği varsayılan seviyeyi belirtir. Varsayılan değer 0'dır. Geçerli aralık 0 ile 9 arasındadır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Belge taslağında (Başlık stilleriyle biçimlendirilmiş paragraflar) kaç seviye başlık dahil edileceğini belirtir. Varsayılan değer 0'dır. Geçerli aralık 0 ile 9 arasındadır.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Belge taslağında (Başlık stilleriyle biçimlendirilmiş paragraflar) kaç seviye başlık dahil edileceğini belirtir. Varsayılan değer 0'dır. Geçerli aralık 0 ile 9 arasındadır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Dosya görüntülendiğinde belge taslağında kaç seviye genişletilmiş gösterileceğini belirtir. Varsayılan değer 0'dır. Geçerli aralık 0 ile 9 arasındadır. Bu seçeneğin XPS olarak kaydedildiğinde çalışmayacağını unutmayın.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Dosya görüntülendiğinde belge taslağında kaç seviye genişletilmiş gösterileceğini belirtir. Varsayılan değer 0'dır. Geçerli aralık 0 ile 9 arasındadır. Bu seçeneğin XPS olarak kaydedildiğinde çalışmayacağını unutmayın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

