---
title: "WordProcessingLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti WordProcessing."
type: docs
weight: 40
url: /it/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti WordProcessing.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Inizializza una nuova istanza della classe [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Carattere predefinito per il documento Words. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Carattere predefinito per il documento Words. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | Se AutoFontSubstitution è disabilitato, GroupDocs.Conversion utilizza DefaultFont per la sostituzione dei caratteri mancanti. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | Se AutoFontSubstitution è disabilitato, GroupDocs.Conversion utilizza DefaultFont per la sostituzione dei caratteri mancanti. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sostituisci caratteri specifici durante la conversione del documento Words. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | Se EmbedTrueTypeFonts è true, GroupDocs.Conversion incorpora i caratteri TrueType nel documento di output. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Aggiorna il layout della pagina dopo il caricamento. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Aggiorna i campi dopo il caricamento. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Mantieni il valore originale del campo data. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Imposta Mantieni valore originale del campo data. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sostituisci caratteri specifici durante la conversione del documento Words. |
|
|  | [getPassword()](#getPassword--) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Nascondi markup e tracciamento delle modifiche per i documenti Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Nascondi markup e tracciamento delle modifiche per i documenti Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Nascondi i commenti. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Opzioni dei segnalibri |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Opzioni dei segnalibri |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Specifica se conservare i campi modulo di Microsoft Word come campi modulo nel PDF o convertirli in testo. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | Imposta il flag preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Specifica se utilizzare un text shaper per una migliore visualizzazione del kerning. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Specifica se utilizzare un text shaper per una migliore visualizzazione del kerning. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | Determina se la struttura del documento deve essere conservata durante la conversione in PDF (il valore predefinito è false). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Specifica come i commenti devono essere visualizzati nel documento di output. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Mostra il nome completo del commentatore nei commenti. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Abilita o disabilita la generazione della numerazione delle pagine nel documento convertito. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | Ottiene le opzioni di sillabazione per i documenti WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | Imposta le opzioni di sillabazione per i documenti WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | Recupera il flag InterruptThreadIfImageExceptionThrown Predefinito: false. Se true, interrompe il thread di conversione principale se si verifica un'eccezione in un thread di elaborazione immagine. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | Imposta il flag InterruptThreadIfImageExceptionThrown |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Quando abilitato (predefinito), i paragrafi e le run il cui testo è prevalentemente da destra a sinistra (RTL) avranno i loro flag bidi corretti prima della conversione. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | Imposta l'autoDetectRtlDirection |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Inizializza una nuova istanza della classe [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions).


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font predefinito per i documenti Words. Il font seguente verrà utilizzato se un font è mancante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font predefinito per i documenti Words. Il font seguente verrà utilizzato se un font è mancante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Se AutoFontSubstitution è disabilitato, GroupDocs.Conversion utilizza il DefaultFont per la sostituzione dei font mancanti. Se AutoFontSubstitution è abilitato,
GroupDocs.Conversion valuta tutti i campi correlati in FontInfo (Panose, Sig ecc.) per il font mancante e trova la corrispondenza più vicina tra le font disponibili.
Nota che il meccanismo di sostituzione dei font sovrascriverà il DefaultFont nei casi in cui FontInfo per il font mancante sia disponibile nel documento. Il valore predefinito è True.


**Returns:**
booleano
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Se AutoFontSubstitution è disabilitato, GroupDocs.Conversion utilizza il DefaultFont per la sostituzione dei font mancanti. Se AutoFontSubstitution è abilitato,
GroupDocs.Conversion valuta tutti i campi correlati in FontInfo (Panose, Sig ecc.) per il font mancante e trova la corrispondenza più vicina tra le font disponibili.
Nota che il meccanismo di sostituzione dei font sovrascriverà il DefaultFont nei casi in cui FontInfo per il font mancante sia disponibile nel documento. Il valore predefinito è True.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sostituisci caratteri specifici durante la conversione del documento Words.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Se EmbedTrueTypeFonts è true, GroupDocs.Conversion incorpora i font TrueType nel documento di output. Predefinito: false


**Returns:**
booleano
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| embedTrueTypeFonts | booleano |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Aggiorna il layout della pagina dopo il caricamento. Predefinito: false


**Returns:**
booleano
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| updatePageLayout | booleano |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Aggiorna i campi dopo il caricamento. Predefinito: false


**Returns:**
booleano
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| updateFields | booleano |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Mantieni il valore originale del campo data. Predefinito: false


**Returns:**
booleano
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Imposta Mantieni valore originale del campo data.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keepDateFieldOriginalValue | booleano |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sostituisci caratteri specifici durante la conversione del documento Words.


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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Nascondi markup e tracciamento delle modifiche per i documenti Word.


**Returns:**
booleano
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Nascondi markup e tracciamento delle modifiche per i documenti Word.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Nascondi i commenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Opzioni dei segnalibri


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Opzioni dei segnalibri


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Specifica se preservare i campi modulo di Microsoft Word come campi modulo nel PDF o convertirli in testo. Il valore predefinito è false.


**Returns:**
boolean - flag preserveFontFields

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


Imposta il flag preserveFontFields


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | preserveFontFields | booleano | preserva i campi modulo di Microsoft Word come campi modulo nel PDF o li converte in testo |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Specifica se utilizzare un text shaper per una migliore visualizzazione del kerning. Il valore predefinito è false.


**Returns:**
booleano
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Specifica se utilizzare un text shaper per una migliore visualizzazione del kerning. Il valore predefinito è false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | isUseTextShaper | booleano | flag isUseTextShaper |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


Determina se la struttura del documento deve essere preservata durante la conversione in PDF (il valore predefinito è false). Nota che l'esportazione della struttura del documento aumenta significativamente il consumo di memoria, soprattutto per i documenti di grandi dimensioni.


**Returns:**
booleano
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| preserveDocumentStructure | booleano |  |

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

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Specifica come i commenti devono essere visualizzati nel documento di output. Il valore predefinito è ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Mostra il nome completo del commentatore nei commenti. Il valore predefinito è false.


**Returns:**
booleano
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| showFullCommenterName | booleano |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Abilita o disabilita la generazione della numerazione di pagina nel documento convertito. Predefinito: false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


Ottiene le opzioni di sillabazione per i documenti WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


Imposta le opzioni di sillabazione per i documenti WordProcessing.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


Recupera il flag InterruptThreadIfImageExceptionThrown Predefinito: false. Se true, interrompe il thread di conversione principale se si verifica un'eccezione in un thread di elaborazione immagine.


**Returns:**
booleano
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


Imposta il flag InterruptThreadIfImageExceptionThrown


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | booleano |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Quando abilitato (predefinito), i paragrafi e le run il cui testo è prevalentemente da destra a sinistra (RTL) avranno i loro flag bidi corretti prima della conversione.


Questo corrisponde all'euristica applicata da Microsoft Word e LibreOffice e
corregge il rendering di documenti arabi/ebraici prodotti da generatori
(in particolare Google Docs) che emettono OOXML senza


e con

su sequenze contenenti solo script RTL.


Imposta a
false
per preservare un'interpretazione OOXML rigorosa del
markup di origine.


**Returns:**
booleano
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


Imposta l'autoDetectRtlDirection


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | autoDetectRtlDirection | booleano | autoDetectRtlDirection |
|

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

