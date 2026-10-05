---
title: "WordProcessingBookmarksOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "WordProcessing içinde yer imlerini işleme seçenekleri."
type: docs
weight: 43
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

WordProcessing içinde yer imlerini işleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Word yer imlerinin gösterileceği belge taslağındaki varsayılan seviyeyi belirtir. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Word yer imlerinin gösterileceği belge taslağındaki varsayılan seviyeyi belirtir. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Belge taslağına dahil edilecek başlık seviyelerinin (Başlık stilleriyle biçimlendirilmiş paragraflar) sayısını belirtir. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Belge taslağına dahil edilecek başlık seviyelerinin (Başlık stilleriyle biçimlendirilmiş paragraflar) sayısını belirtir. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Dosya görüntülendiğinde belge taslağında kaç seviyenin genişletilmiş gösterileceğini belirtir. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Dosya görüntülendiğinde belge taslağında kaç seviyenin genişletilmiş gösterileceğini belirtir. |
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Word yer imlerinin gösterileceği belge taslağındaki varsayılan seviyeyi belirtir. Varsayılan 0'dır. Geçerli aralık 0 ile 9 arasındadır.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Word yer imlerinin gösterileceği belge taslağındaki varsayılan seviyeyi belirtir. Varsayılan 0'dır. Geçerli aralık 0 ile 9 arasındadır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Belge taslağına dahil edilecek başlık seviyelerinin (Başlık stilleriyle biçimlendirilmiş paragraflar) sayısını belirtir. Varsayılan 0'dır. Geçerli aralık 0 ile 9 arasındadır.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Belge taslağına dahil edilecek başlık seviyelerinin (Başlık stilleriyle biçimlendirilmiş paragraflar) sayısını belirtir. Varsayılan 0'dır. Geçerli aralık 0 ile 9 arasındadır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Dosya görüntülendiğinde belge taslağında kaç seviyenin genişletilmiş gösterileceğini belirtir. Varsayılan 0'dır. Geçerli aralık 0 ile 9 arasındadır. Bu seçeneğin XPS olarak kaydedildiğinde çalışmayacağını unutmayın.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Dosya görüntülendiğinde belge taslağında kaç seviyenin genişletilmiş gösterileceğini belirtir. Varsayılan 0'dır. Geçerli aralık 0 ile 9 arasındadır. Bu seçeneğin XPS olarak kaydedildiğinde çalışmayacağını unutmayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

