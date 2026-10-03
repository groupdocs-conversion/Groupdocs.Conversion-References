---
title: "TxtLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Txt."
type: docs
weight: 34
url: /it/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Opzioni per il caricamento dei documenti Txt.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Inizializza una nuova istanza della classe [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Consente di specificare come vengono riconosciuti gli elementi di elenchi numerati quando un documento di testo semplice viene convertito. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Consente di specificare come vengono riconosciuti gli elementi di elenchi numerati quando un documento di testo semplice viene convertito. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. |
|
|  | [getEncoding()](#getEncoding--) | Ottiene o imposta la codifica che verrà utilizzata durante il caricamento del documento Txt. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ottiene o imposta la codifica che verrà utilizzata durante il caricamento del documento Txt. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Inizializza una nuova istanza della classe [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Consente di specificare come vengono riconosciuti gli elementi di elenchi numerati quando un documento di testo semplice viene convertito.
Il valore predefinito è true.

<br />

*** ** * ** ***

Se questa opzione è impostata su false, l'algoritmo di riconoscimento delle liste rileva i paragrafi di elenco, quando i numeri di elenco terminano con
sia punto, parentesi chiusa o simboli di elenco (come "\u2022", "*", "-" o "o").

Se questa opzione è impostata su true, gli spazi bianchi sono anche usati come delimitatori dei numeri di elenco:
L'algoritmo di riconoscimento delle liste per la numerazione in stile arabo (1., 1.1.2.) utilizza sia spazi bianchi sia il punto (".") come simboli.

<br />



**Returns:**
booleano
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Consente di specificare come vengono riconosciuti gli elementi di elenchi numerati quando un documento di testo semplice viene convertito.
Il valore predefinito è true.

<br />

*** ** * ** ***

Se questa opzione è impostata su false, l'algoritmo di riconoscimento delle liste rileva i paragrafi di elenco, quando i numeri di elenco terminano con
sia punto, parentesi chiusa o simboli di elenco (come "\u2022", "*", "-" o "o").

Se questa opzione è impostata su true, gli spazi bianchi sono anche usati come delimitatori dei numeri di elenco:
L'algoritmo di riconoscimento delle liste per la numerazione in stile arabo (1., 1.1.2.) utilizza sia spazi bianchi sia il punto (".") come simboli.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi finali.
Il valore predefinito è [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi finali.
Il valore predefinito è [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali.
Il valore predefinito è [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali.
Il valore predefinito è [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Ottiene o imposta la codifica che verrà usata durante il caricamento del documento Txt. Può essere null. Il valore predefinito è null.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Ottiene o imposta la codifica che verrà usata durante il caricamento del documento Txt. Può essere null. Il valore predefinito è null.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

