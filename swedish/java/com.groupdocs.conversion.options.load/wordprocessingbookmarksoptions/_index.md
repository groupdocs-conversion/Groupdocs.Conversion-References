---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för hantering av bokmärken i WordProcessing"
type: docs
weight: 39
url: /sv/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Alternativ för hantering av bokmärken i WordProcessing

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Anger standardnivån i dokumentöversikten där Word-bokmärken ska visas. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Anger standardnivån i dokumentöversikten där Word-bokmärken ska visas. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Anger hur många rubriknivåer (paragrafer formaterade med rubrikstilar) som ska inkluderas i dokumentöversikten. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Anger hur många rubriknivåer (paragrafer formaterade med rubrikstilar) som ska inkluderas i dokumentöversikten. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Anger hur många nivåer i dokumentöversikten som ska visas expanderade när filen visas. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Anger hur många nivåer i dokumentöversikten som ska visas expanderade när filen visas. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Anger standardnivån i dokumentöversikten där Word-bokmärken ska visas. Standard är 0. Giltigt intervall är 0 till 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Anger standardnivån i dokumentöversikten där Word-bokmärken ska visas. Standard är 0. Giltigt intervall är 0 till 9.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Anger hur många rubriknivåer (paragrafer formaterade med rubrikstilar) som ska inkluderas i dokumentöversikten. Standard är 0. Giltigt intervall är 0 till 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Anger hur många rubriknivåer (paragrafer formaterade med rubrikstilar) som ska inkluderas i dokumentöversikten. Standard är 0. Giltigt intervall är 0 till 9.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Anger hur många nivåer i dokumentöversikten som ska visas expanderade när filen visas. Standard är 0. Giltigt intervall är 0 till 9. Observera att detta alternativ inte fungerar vid sparande till XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Anger hur många nivåer i dokumentöversikten som ska visas expanderade när filen visas. Standard är 0. Giltigt intervall är 0 till 9. Observera att detta alternativ inte fungerar vid sparande till XPS.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

