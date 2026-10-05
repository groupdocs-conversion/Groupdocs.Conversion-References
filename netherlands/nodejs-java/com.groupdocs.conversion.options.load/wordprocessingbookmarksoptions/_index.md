---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het verwerken van bladwijzers in WordProcessing"
type: docs
weight: 43
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Opties voor het verwerken van bladwijzers in WordProcessing
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Specificeert het standaardniveau in de documentstructuur waarop Word-bladwijzers worden weergegeven. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Specificeert het standaardniveau in de documentstructuur waarop Word-bladwijzers worden weergegeven. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Specificeert hoeveel niveaus van koppen (alinea's opgemaakt met de Kop-stijlen) moeten worden opgenomen in de documentstructuur. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Specificeert hoeveel niveaus van koppen (alinea's opgemaakt met de Kop-stijlen) moeten worden opgenomen in de documentstructuur. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Specificeert hoeveel niveaus in de documentstructuur moeten worden uitgeklapt wanneer het bestand wordt bekeken. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Specificeert hoeveel niveaus in de documentstructuur moeten worden uitgeklapt wanneer het bestand wordt bekeken. |
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Specificeert het standaardniveau in de documentstructuur waarop Word-bladwijzers worden weergegeven. Standaard is 0. Geldig bereik is 0 tot 9.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Specificeert het standaardniveau in de documentstructuur waarop Word-bladwijzers worden weergegeven. Standaard is 0. Geldig bereik is 0 tot 9.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Specificeert hoeveel niveaus van koppen (alinea's opgemaakt met de Kop-stijlen) moeten worden opgenomen in de documentstructuur. Standaard is 0. Geldig bereik is 0 tot 9.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Specificeert hoeveel niveaus van koppen (alinea's opgemaakt met de Kop-stijlen) moeten worden opgenomen in de documentstructuur. Standaard is 0. Geldig bereik is 0 tot 9.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Specificeert hoeveel niveaus in de documentstructuur moeten worden uitgeklapt wanneer het bestand wordt bekeken. Standaard is 0. Geldig bereik is 0 tot 9. Let op: deze optie werkt niet bij het opslaan naar XPS.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Specificeert hoeveel niveaus in de documentstructuur moeten worden uitgeklapt wanneer het bestand wordt bekeken. Standaard is 0. Geldig bereik is 0 tot 9. Let op: deze optie werkt niet bij het opslaan naar XPS.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

