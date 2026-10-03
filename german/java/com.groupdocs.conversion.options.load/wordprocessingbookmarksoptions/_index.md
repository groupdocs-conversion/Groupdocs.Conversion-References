---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Verwalten von Lesezeichen in WordProcessing"
type: docs
weight: 39
url: /de/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Optionen zum Verwalten von Lesezeichen in WordProcessing

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Gibt die Standardebene in der Dokumentgliederung an, in der Word-Lesezeichen angezeigt werden. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Gibt die Standardebene in der Dokumentgliederung an, in der Word-Lesezeichen angezeigt werden. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Gibt an, wie viele Ebenen von Überschriften (Absätze, die mit den Überschriftsformaten formatiert sind) in die Dokumentgliederung aufgenommen werden sollen. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Gibt an, wie viele Ebenen von Überschriften (Absätze, die mit den Überschriftsformaten formatiert sind) in die Dokumentgliederung aufgenommen werden sollen. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Gibt an, wie viele Ebenen in der Dokumentgliederung beim Anzeigen der Datei erweitert angezeigt werden sollen. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Gibt an, wie viele Ebenen in der Dokumentgliederung beim Anzeigen der Datei erweitert angezeigt werden sollen. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Gibt die Standardebene in der Dokumentgliederung an, in der Word-Lesezeichen angezeigt werden. Standard ist 0. Gültiger Bereich ist 0 bis 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Gibt die Standardebene in der Dokumentgliederung an, in der Word-Lesezeichen angezeigt werden. Standard ist 0. Gültiger Bereich ist 0 bis 9.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Gibt an, wie viele Ebenen von Überschriften (Absätze, die mit den Überschriftsformaten formatiert sind) in die Dokumentgliederung aufgenommen werden sollen. Standard ist 0. Gültiger Bereich ist 0 bis 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Gibt an, wie viele Ebenen von Überschriften (Absätze, die mit den Überschriftsformaten formatiert sind) in die Dokumentgliederung aufgenommen werden sollen. Standard ist 0. Gültiger Bereich ist 0 bis 9.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Gibt an, wie viele Ebenen in der Dokumentgliederung beim Anzeigen der Datei erweitert angezeigt werden sollen. Standard ist 0. Gültiger Bereich ist 0 bis 9. Hinweis: Diese Option funktioniert nicht beim Speichern als XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Gibt an, wie viele Ebenen in der Dokumentgliederung beim Anzeigen der Datei erweitert angezeigt werden sollen. Standard ist 0. Gültiger Bereich ist 0 bis 9. Hinweis: Diese Option funktioniert nicht beim Speichern als XPS.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

