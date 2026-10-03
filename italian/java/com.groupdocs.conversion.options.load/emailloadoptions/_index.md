---
title: "EmailLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Email."
type: docs
weight: 18
url: /it/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Opzioni per il caricamento dei documenti Email.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Inizializza una nuova istanza della classe [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Opzione per visualizzare o nascondere l'intestazione dell'email. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Opzione per visualizzare o nascondere l'intestazione dell'email. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Opzione per visualizzare o nascondere l'indirizzo email "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Opzione per visualizzare o nascondere l'indirizzo email "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Opzione per visualizzare o nascondere l'indirizzo email "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Opzione per visualizzare o nascondere l'indirizzo email "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Opzione per visualizzare o nascondere l'indirizzo email "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Opzione per visualizzare o nascondere l'indirizzo email "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Opzione per visualizzare o nascondere l'indirizzo email "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Opzione per visualizzare o nascondere l'indirizzo email "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Ottiene o imposta il valore di offset del Tempo Coordinato Universale (UTC) per le date dei messaggi. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Timeout per il caricamento di risorse esterne |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Timeout per il caricamento di risorse esterne (impostatore) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Ottiene o imposta il valore di offset del Tempo Coordinato Universale (UTC) per le date dei messaggi. |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza corrente. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Ottiene la mappatura tra il messaggio email e la rappresentazione testuale del campo |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Imposta la mappatura tra il messaggio email e la rappresentazione testuale del campo |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Definisce se è necessario mantenere la stringa originale dell'intestazione della data nel messaggio di posta durante il salvataggio o meno (Il valore predefinito è true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Definisce se è necessario mantenere la stringa originale dell'intestazione della data nel messaggio di posta durante il salvataggio o meno |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Ottiene l'opzione per visualizzare o nascondere gli allegati nell'intestazione. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Imposta l'opzione per visualizzare o nascondere gli allegati nell'intestazione. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Ottiene l'opzione per visualizzare o nascondere l'oggetto nell'intestazione. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Imposta l'opzione per visualizzare o nascondere l'oggetto nell'intestazione |
|
|  | [isDisplaySent()](#isDisplaySent--) | Ottiene l'opzione per visualizzare o nascondere la data/ora di invio nell'intestazione. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Imposta l'opzione per visualizzare o nascondere la data/ora di invio nell'intestazione. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Salta il caricamento delle risorse http se vero |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Inizializza una nuova istanza della classe [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Opzione per visualizzare o nascondere l'intestazione email. Predefinito: true.


**Returns:**
booleano
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Opzione per visualizzare o nascondere l'intestazione email. Predefinito: true.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Opzione per visualizzare o nascondere l'indirizzo email "from". Predefinito: true.


**Returns:**
booleano
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Opzione per visualizzare o nascondere l'indirizzo email "from". Predefinito: true.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Opzione per visualizzare o nascondere l'indirizzo email "to". Predefinito: true.


**Returns:**
booleano
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Opzione per visualizzare o nascondere l'indirizzo email "to". Predefinito: true.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Opzione per visualizzare o nascondere l'indirizzo email "Cc". Predefinito: false.


**Returns:**
booleano
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Opzione per visualizzare o nascondere l'indirizzo email "Cc". Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Opzione per visualizzare o nascondere l'indirizzo email "Bcc". Predefinito: false.


**Returns:**
booleano
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Opzione per visualizzare o nascondere l'indirizzo email "Bcc". Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Ottiene o imposta lo scostamento del Tempo Universale Coordinato (UTC) per le date dei messaggi. Questa proprietà definisce la differenza di fuso orario, tra l'ora locale e UTC.


**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


Timeout per il caricamento di risorse esterne


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Timeout per il caricamento di risorse esterne (impostatore)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Ottiene o imposta lo scostamento del Tempo Universale Coordinato (UTC) per le date dei messaggi. Questa proprietà definisce la differenza di fuso orario, tra l'ora locale e UTC.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona l'istanza corrente.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Ottiene la mappatura tra il messaggio email e la rappresentazione testuale del campo


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - mappatura

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Imposta la mappatura tra il messaggio email e la rappresentazione testuale del campo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | mappatura |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Definisce se è necessario mantenere la stringa originale dell'intestazione della data nel messaggio di posta durante il salvataggio o meno (Il valore predefinito è true)


**Returns:**
boolean - conserva la data originale se vero

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Definisce se è necessario mantenere la stringa originale dell'intestazione della data nel messaggio di posta durante il salvataggio o meno


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | preserveOriginalDate | booleano | conserva la data originale |
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

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Ottiene l'opzione per visualizzare o nascondere gli allegati nell'intestazione. Predefinito: true.


**Returns:**
booleano
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Imposta l'opzione per visualizzare o nascondere gli allegati nell'intestazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| displayAttachments | booleano |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Ottiene l'opzione per visualizzare o nascondere l'oggetto nell'intestazione. Predefinito: true.


**Returns:**
booleano
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Imposta l'opzione per visualizzare o nascondere l'oggetto nell'intestazione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| displaySubject | booleano |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Ottiene l'opzione per visualizzare o nascondere la data/ora di invio nell'intestazione. Predefinito: true.


**Returns:**
booleano
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Imposta l'opzione per visualizzare o nascondere la data/ora di invio nell'intestazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| displaySent | booleano |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Salta il caricamento delle risorse http se vero


**Returns:**
booleano
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| skipExternalResources | booleano |  |

