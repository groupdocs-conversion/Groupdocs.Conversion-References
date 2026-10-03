---
title: "PdfLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Pdf."
type: docs
weight: 27
url: /it/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti Pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Inizializza una nuova istanza della classe [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Rimuove i file incorporati. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Rimuove i file incorporati. |
|
|  | [getPassword()](#getPassword--) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Font predefinito per il documento Pdf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font predefinito per il documento Pdf. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sostituisce font specifici durante la conversione del documento Pdf. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sostituisce font specifici durante la conversione del documento Pdf. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Nasconde le annotazioni nei documenti Pdf. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Nasconde le annotazioni nei documenti Pdf. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Appiattisce tutti i campi del modulo PDF. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Appiattisce tutti i campi del modulo PDF. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Reimposta le cartelle dei font prima di caricare il documento. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Abilita o disabilita la generazione della numerazione delle pagine nel documento convertito. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Ottiene il flag Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Imposta il flag Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Specifica se il documento proprietario deve essere convertito. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Specifica se il documento proprietario deve essere convertito. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Specifica se i documenti di proprietà devono essere convertiti. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Specifica se i documenti di proprietà devono essere convertiti. |
|
|  | [getDepth()](#getDepth--) | Profondità massima per l'elaborazione dei documenti di proprietà. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Profondità massima per l'elaborazione dei documenti di proprietà. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Inizializza una nuova istanza della classe [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Rimuove i file incorporati.


**Returns:**
booleano
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Rimuove i file incorporati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font predefinito per il documento Pdf.
Il font seguente verrà utilizzato se un font è mancante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font predefinito per il documento Pdf.
Il font seguente verrà utilizzato se un font è mancante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sostituisce font specifici durante la conversione del documento Pdf.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sostituisce font specifici durante la conversione del documento Pdf.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Nasconde le annotazioni nei documenti Pdf.


**Returns:**
booleano
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Nasconde le annotazioni nei documenti Pdf.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Appiattisce tutti i campi del modulo PDF.


**Returns:**
booleano
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Appiattisce tutti i campi del modulo PDF.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reimposta le cartelle dei font prima di caricare il documento.


**Returns:**
booleano
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resetFontFolders | booleano |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Abilita o disabilita la generazione della numerazione di pagina nel documento convertito. Predefinito: false.


**Returns:**
booleano
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isPageNumbering | booleano |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Ottiene il flag Remove JavaScript.


**Returns:**
booleano
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Imposta il flag Remove JavaScript.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| removeJavascript | booleano |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Specifica se il documento proprietario deve essere convertito.

Il valore predefinito è
true
.


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Specifica se il documento proprietario deve essere convertito.

Il valore predefinito è
true
.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Specifica se i documenti di proprietà devono essere convertiti.

Il valore predefinito è
false
.


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Specifica se i documenti di proprietà devono essere convertiti.

Il valore predefinito è
false
.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Profondità massima per l'elaborazione dei documenti di proprietà.

Il valore predefinito è
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Profondità massima per l'elaborazione dei documenti di proprietà.

Il valore predefinito è
2
.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| depth | int |  |

