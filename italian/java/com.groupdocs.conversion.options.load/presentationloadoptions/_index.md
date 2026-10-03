---
title: "PresentationLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Presentation."
type: docs
weight: 29
url: /it/java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti Presentation.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationLoadOptions()](#PresentationLoadOptions--) | Inizializza una nuova istanza della classe [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Carattere predefinito per il rendering della presentazione. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Carattere predefinito per il rendering della presentazione. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sostituisci i caratteri specifici durante la conversione del documento Presentation. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sostituisci i caratteri specifici durante la conversione del documento Presentation. |
|
|  | [getPassword()](#getPassword--) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [getHideComments()](#getHideComments--) | Nascondi i commenti. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Nascondi i commenti. |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Mostra diapositive nascoste. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Mostra diapositive nascoste. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
|  | [getNotesPosition()](#getNotesPosition--) | Rappresenta il modo in cui i commenti vengono stampati con la diapositiva. |
|
|  | [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | Rappresenta il modo in cui le note vengono stampate con la diapositiva. |
|
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


Inizializza una nuova istanza della classe [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Carattere predefinito per il rendering della presentazione. Il carattere seguente verrà utilizzato se manca un carattere nella presentazione.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Carattere predefinito per il rendering della presentazione. Il carattere seguente verrà utilizzato se manca un carattere nella presentazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sostituisci i caratteri specifici durante la conversione del documento Presentation.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sostituisci i caratteri specifici durante la conversione del documento Presentation.


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

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Nascondi i commenti.


**Returns:**
booleano
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Nascondi i commenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Mostra diapositive nascoste.


**Returns:**
booleano
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Mostra diapositive nascoste.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Se true tutte le risorse esterne non verranno caricate, ad eccezione delle risorse nella


**Returns:**
booleano
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| skip | booleano |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Risorse esterne che saranno sempre caricate


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getDocumentFontSources() {#getDocumentFontSources--}
```
public List<String> getDocumentFontSources()
```




**Returns:**
java.util.List<java.lang.String>
### setDocumentFontSources(List<String> documentFontSources) {#setDocumentFontSources-java.util.List-java.lang.String--}
```
public void setDocumentFontSources(List<String> documentFontSources)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


Rappresenta il modo in cui i commenti vengono stampati con la diapositiva. Il valore predefinito è Nessuno.


**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


Rappresenta il modo in cui le note vengono stampate con la diapositiva. Il valore predefinito è Nessuno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| notesPosition | [PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition) |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public PresentationCommentsPosition getCommentsPosition()
```




**Returns:**
[PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) - 
### setCommentsPosition(PresentationCommentsPosition commentsPosition) {#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-}
```
public void setCommentsPosition(PresentationCommentsPosition commentsPosition)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ottiene l'opzione per controllare se il contenitore dei documenti stesso deve essere convertito


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opzione per controllare se i documenti di proprietà nel contenitore dei documenti devono essere convertiti


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opzione per controllare quanti livelli di profondità eseguire la conversione


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| depth | int |  |

