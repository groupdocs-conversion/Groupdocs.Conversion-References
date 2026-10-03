---
title: "RecognizedImage"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta il testo estratto da un'immagine come risultato del suo processo di riconoscimento."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Rappresenta il testo, estratto da un'immagine come risultato del suo processo di riconoscimento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Inizializza una nuova istanza della classe, utilizzando un insieme di righe riconosciute. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [EMPTY](#EMPTY) | Immagine riconosciuta vuota |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLines()](#getLines--) | Restituisce le righe di testo, con i loro frammenti, riconosciute all'interno del documento. |
|
|  | [getText()](#getText--) | Restituisce l'equivalente testuale del testo strutturato |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Inizializza una nuova istanza della classe, utilizzando un insieme di righe riconosciute.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | righe | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | un IEnumerable (ad esempio una lista o un array) di righe riconosciute |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Immagine riconosciuta vuota


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Restituisce le righe di testo, con i loro frammenti, riconosciute all'interno del documento.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Restituisce l'equivalente testuale del testo strutturato


**Returns:**
java.lang.String
