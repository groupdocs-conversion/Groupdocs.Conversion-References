---
title: "TextLine"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta il testo estratto da un'immagine come risultato del suo processo di riconoscimento."
type: docs
weight: 12
url: /it/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Rappresenta il testo, estratto da un'immagine come risultato del suo processo di riconoscimento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Inizializza una nuova istanza di una riga di testo, estratta dal motore OCR da un'immagine. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFragments()](#getFragments--) | Restituisce un array di frammenti di testo, come simboli e parole, riconosciuti nella riga. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Inizializza una nuova istanza di una riga di testo, estratta dal motore OCR da un'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | frammenti | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | insieme iniziale di frammenti di testo |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Restituisce un array di frammenti di testo, come simboli e parole, riconosciuti nella riga.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
