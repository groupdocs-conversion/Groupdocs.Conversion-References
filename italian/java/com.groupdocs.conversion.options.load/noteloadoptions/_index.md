---
title: "NoteLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti One."
type: docs
weight: 24
url: /it/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Opzioni per il caricamento dei documenti One.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | Inizializza una nuova istanza della classe [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Carattere predefinito per il documento Note. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Carattere predefinito per il documento Note. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sostituisce caratteri specifici durante la conversione del documento Note. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sostituisce caratteri specifici durante la conversione del documento Note. |
|
|  | [getPassword()](#getPassword--) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per rimuovere la protezione del documento protetto. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Inizializza una nuova istanza della classe [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Carattere predefinito per il documento Note. Il carattere seguente verrà utilizzato se un carattere è mancante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Carattere predefinito per il documento Note. Il carattere seguente verrà utilizzato se un carattere è mancante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sostituisce caratteri specifici durante la conversione del documento Note.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sostituisce caratteri specifici durante la conversione del documento Note.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Imposta la password per rimuovere la protezione del documento protetto.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta la password per rimuovere la protezione del documento protetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

