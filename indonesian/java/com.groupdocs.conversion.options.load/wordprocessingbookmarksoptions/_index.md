---
title: "WordProcessingBookmarksOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk menangani bookmark dalam WordProcessing"
type: docs
weight: 39
url: /id/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Opsi untuk menangani bookmark dalam WordProcessing

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Menentukan level default dalam outline dokumen di mana bookmark Word akan ditampilkan. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Menentukan level default dalam outline dokumen di mana bookmark Word akan ditampilkan. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Menentukan berapa banyak tingkat heading (paragraf yang diformat dengan gaya Heading) yang akan disertakan dalam outline dokumen. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Menentukan berapa banyak tingkat heading (paragraf yang diformat dengan gaya Heading) yang akan disertakan dalam outline dokumen. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Menentukan berapa banyak tingkat dalam outline dokumen yang akan ditampilkan secara diperluas saat file dilihat. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Menentukan berapa banyak tingkat dalam outline dokumen yang akan ditampilkan secara diperluas saat file dilihat. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Menentukan tingkat default dalam outline dokumen tempat menampilkan bookmark Word. Defaultnya adalah 0. Rentang yang valid adalah 0 hingga 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Menentukan tingkat default dalam outline dokumen tempat menampilkan bookmark Word. Defaultnya adalah 0. Rentang yang valid adalah 0 hingga 9.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Menentukan berapa banyak tingkat heading (paragraf yang diformat dengan gaya Heading) yang akan disertakan dalam outline dokumen. Defaultnya adalah 0. Rentang yang valid adalah 0 hingga 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Menentukan berapa banyak tingkat heading (paragraf yang diformat dengan gaya Heading) yang akan disertakan dalam outline dokumen. Defaultnya adalah 0. Rentang yang valid adalah 0 hingga 9.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Menentukan berapa banyak tingkat dalam outline dokumen yang akan ditampilkan secara diperluas saat file dilihat. Defaultnya adalah 0. Rentang yang valid adalah 0 hingga 9. Catatan bahwa opsi ini tidak akan berfungsi saat menyimpan ke XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Menentukan berapa banyak tingkat dalam outline dokumen yang akan ditampilkan secara diperluas saat file dilihat. Defaultnya adalah 0. Rentang yang valid adalah 0 hingga 9. Catatan bahwa opsi ini tidak akan berfungsi saat menyimpan ke XPS.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

