---
title: "WordProcessingBookmarksOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la gestione dei segnalibri in WordProcessing"
type: docs
weight: 39
url: /it/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Opzioni per la gestione dei segnalibri in WordProcessing

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Specifica il livello predefinito nella struttura del documento in cui visualizzare i segnalibri Word. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Specifica il livello predefinito nella struttura del documento in cui visualizzare i segnalibri Word. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Specifica quanti livelli di intestazioni (paragrafi formattati con gli stili Intestazione) includere nella struttura del documento. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Specifica quanti livelli di intestazioni (paragrafi formattati con gli stili Intestazione) includere nella struttura del documento. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Specifica quanti livelli nella struttura del documento mostrare espansi quando il file viene visualizzato. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Specifica quanti livelli nella struttura del documento mostrare espansi quando il file viene visualizzato. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Specifica il livello predefinito nella struttura del documento in cui visualizzare i segnalibri di Word. Il valore predefinito è 0. L'intervallo valido è da 0 a 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Specifica il livello predefinito nella struttura del documento in cui visualizzare i segnalibri di Word. Il valore predefinito è 0. L'intervallo valido è da 0 a 9.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Specifica quanti livelli di intestazioni (paragrafi formattati con gli stili Intestazione) includere nella struttura del documento. Il valore predefinito è 0. L'intervallo valido è da 0 a 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Specifica quanti livelli di intestazioni (paragrafi formattati con gli stili Intestazione) includere nella struttura del documento. Il valore predefinito è 0. L'intervallo valido è da 0 a 9.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Specifica quanti livelli nella struttura del documento mostrare espansi quando il file viene visualizzato. Il valore predefinito è 0. L'intervallo valido è da 0 a 9. Nota che questa opzione non funzionerà durante il salvataggio in XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Specifica quanti livelli nella struttura del documento mostrare espansi quando il file viene visualizzato. Il valore predefinito è 0. L'intervallo valido è da 0 a 9. Nota che questa opzione non funzionerà durante il salvataggio in XPS.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

