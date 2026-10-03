---
title: "EmailLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents d'e-mail."
type: docs
weight: 18
url: /fr/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Options de chargement des documents d'e-mail.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Initialise une nouvelle instance de la classe [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Option d'afficher ou de masquer l'en-tête du courriel. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Option d'afficher ou de masquer l'en-tête du courriel. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Option d'afficher ou de masquer l'adresse e‑mail "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Option d'afficher ou de masquer l'adresse e‑mail "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Option d'afficher ou de masquer l'adresse e‑mail "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Option d'afficher ou de masquer l'adresse e‑mail "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Option d'afficher ou de masquer l'adresse e‑mail "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Option d'afficher ou de masquer l'adresse e‑mail "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Option d'afficher ou de masquer l'adresse e‑mail "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Option d'afficher ou de masquer l'adresse e‑mail "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Obtient ou définit le décalage UTC (Coordinated Universal Time) pour les dates des messages. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Délai d'attente pour le chargement des ressources externes |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Délai d'attente pour le chargement des ressources externes (mutateur) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Obtient ou définit le décalage UTC (Coordinated Universal Time) pour les dates des messages. |
|
|  | [deepClone()](#deepClone--) | Clone l'instance actuelle. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Obtient le mappage entre le message e‑mail et la représentation textuelle du champ |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Définit le mappage entre le message e‑mail et la représentation textuelle du champ |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Définit s'il faut conserver la chaîne d'en-tête de date originale dans le message e‑mail lors de l'enregistrement ou non (valeur par défaut : true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Définit s'il faut conserver la chaîne d'en-tête de date originale dans le message e‑mail lors de l'enregistrement ou non |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Obtient l'option d'afficher ou de masquer les pièces jointes dans l'en-tête. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Définit l'option d'afficher ou de masquer les pièces jointes dans l'en-tête. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Obtient l'option d'afficher ou de masquer le sujet dans l'en-tête. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Définit l'option d'afficher ou de masquer le sujet dans l'en-tête |
|
|  | [isDisplaySent()](#isDisplaySent--) | Obtient l'option d'afficher ou de masquer la date/heure d'envoi dans l'en-tête. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Définit l'option d'afficher ou de masquer la date/heure d'envoi dans l'en-tête. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Ignore le chargement des ressources http si vrai |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Initialise une nouvelle instance de la classe [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Option d'afficher ou de masquer l'en-tête du courriel. Valeur par défaut : vrai.


**Returns:**
booléen
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Option d'afficher ou de masquer l'en-tête du courriel. Valeur par défaut : vrai.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Option d'afficher ou de masquer l'adresse e‑mail « de ». Valeur par défaut : vrai.


**Returns:**
booléen
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Option d'afficher ou de masquer l'adresse e‑mail « de ». Valeur par défaut : vrai.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Option d'afficher ou de masquer l'adresse e‑mail « à ». Valeur par défaut : vrai.


**Returns:**
booléen
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Option d'afficher ou de masquer l'adresse e‑mail « à ». Valeur par défaut : vrai.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Option d'afficher ou de masquer l'adresse e‑mail « Cc ». Valeur par défaut : faux.


**Returns:**
booléen
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Option d'afficher ou de masquer l'adresse e‑mail « Cc ». Valeur par défaut : faux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Option d'afficher ou de masquer l'adresse e‑mail « Cci ». Valeur par défaut : faux.


**Returns:**
booléen
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Option d'afficher ou de masquer l'adresse e‑mail « Cci ». Valeur par défaut : faux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Obtient ou définit le décalage par rapport au Temps Universel Coordonné (UTC) pour les dates des messages. Cette propriété définit la différence de fuseau horaire entre l'heure locale et UTC.


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


Délai d'attente pour le chargement des ressources externes


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Délai d'attente pour le chargement des ressources externes (mutateur)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Obtient ou définit le décalage par rapport au Temps Universel Coordonné (UTC) pour les dates des messages. Cette propriété définit la différence de fuseau horaire entre l'heure locale et UTC.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clone l'instance actuelle.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Obtient le mappage entre le message e‑mail et la représentation textuelle du champ


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - mappage

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Définit le mappage entre le message e‑mail et la représentation textuelle du champ


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | mappage |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Définit s'il faut conserver la chaîne d'en-tête de date originale dans le message e‑mail lors de l'enregistrement ou non (valeur par défaut : true)


**Returns:**
booléen - conserver la date d'origine si vrai

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Définit s'il faut conserver la chaîne d'en-tête de date originale dans le message e‑mail lors de l'enregistrement ou non


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | preserveOriginalDate | booléen | conserver la date d'origine |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtient l'option permettant de contrôler si le conteneur du document doit être converti


**Returns:**
booléen
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwner | booléen |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option pour contrôler si les documents possédés dans le conteneur de documents doivent être convertis


**Returns:**
booléen
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| convertOwned | booléen |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option pour contrôler le nombre de niveaux de profondeur à convertir


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Obtient l'option d'afficher ou de masquer les pièces jointes dans l'en-tête. Valeur par défaut : vrai.


**Returns:**
booléen
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Définit l'option d'afficher ou de masquer les pièces jointes dans l'en-tête.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| displayAttachments | booléen |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Obtient l'option d'afficher ou de masquer le sujet dans l'en-tête. Valeur par défaut : vrai.


**Returns:**
booléen
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Définit l'option d'afficher ou de masquer le sujet dans l'en-tête


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| displaySubject | booléen |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Obtient l'option d'afficher ou de masquer la date/heure d'envoi dans l'en-tête. Valeur par défaut : vrai.


**Returns:**
booléen
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Définit l'option d'afficher ou de masquer la date/heure d'envoi dans l'en-tête.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| displaySent | booléen |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Ignore le chargement des ressources http si vrai


**Returns:**
booléen
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| skipExternalResources | booléen |  |

