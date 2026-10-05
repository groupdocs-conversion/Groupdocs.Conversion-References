---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van e-maildocumenten."
type: docs
weight: 19
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Opties voor het laden van e-maildocumenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmailLoadOptions()](#EmailLoadOptions--) | Initialiseert een nieuwe instantie van de klasse [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDisplayHeader()](#getDisplayHeader--) | Optie om de e-mailheader weer te geven of te verbergen. |
| [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Optie om de e-mailheader weer te geven of te verbergen. |
| [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Optie om het "from" e-mailadres weer te geven of te verbergen. |
| [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Optie om het "from" e-mailadres weer te geven of te verbergen. |
| [getDisplayEmailAddress()](#getDisplayEmailAddress--) | Optie om het e-mailadres weer te geven of te verbergen. |
| [setDisplayEmailAddress(boolean value)](#setDisplayEmailAddress-boolean-) | Optie om het e-mailadres weer te geven of te verbergen. |
| [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Optie om het "to" e-mailadres weer te geven of te verbergen. |
| [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Optie om het "to" e-mailadres weer te geven of te verbergen. |
| [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Optie om het "Cc" e-mailadres weer te geven of te verbergen. |
| [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Optie om het "Cc" e-mailadres weer te geven of te verbergen. |
| [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Optie om het "Bcc" e-mailadres weer te geven of te verbergen. |
| [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Optie om het "Bcc" e-mailadres weer te geven of te verbergen. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Haalt op of stelt de Coordinated Universal Time (UTC)-offset voor de berichtdatums in. |
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Time-out voor het laden van externe bronnen |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Time-out voor het laden van externe bronnen (setter) |
| [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Haalt op of stelt de Coordinated Universal Time (UTC)-offset voor de berichtdatums in. |
| [deepClone()](#deepClone--) | Kloont huidige instantie. |
| [getFieldTextMap()](#getFieldTextMap--) | Haalt de mapping tussen e-mailbericht en veldtekstrepresentatie op |
| [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Stelt de mapping tussen e-mailbericht en veldtekstrepresentatie in |
| [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Definieert of de originele datumheaderstring in het e-mailbericht moet worden behouden bij het opslaan of niet (standaardwaarde is true) |
| [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Definieert of de originele datumheaderstring in het e-mailbericht moet worden behouden bij het opslaan of niet |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Initialiseert een nieuwe instantie van de klasse [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).

### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Optie om de e-mailkop weer te geven of te verbergen. Standaard: true.

**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Optie om de e-mailkop weer te geven of te verbergen. Standaard: true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Optie om het "van" e-mailadres weer te geven of te verbergen. Standaard: true.

**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Optie om het "van" e-mailadres weer te geven of te verbergen. Standaard: true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayEmailAddress() {#getDisplayEmailAddress--}
```
public final boolean getDisplayEmailAddress()
```


Optie om het e-mailadres weer te geven of te verbergen. Standaard: true.

**Returns:**
boolean
### setDisplayEmailAddress(boolean value) {#setDisplayEmailAddress-boolean-}
```
public final void setDisplayEmailAddress(boolean value)
```


Optie om het e-mailadres weer te geven of te verbergen. Standaard: true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Optie om het "aan" e-mailadres weer te geven of te verbergen. Standaard: true.

**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Optie om het "aan" e-mailadres weer te geven of te verbergen. Standaard: true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Optie om het "Cc" e-mailadres weer te geven of te verbergen. Standaard: false.

**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Optie om het "Cc" e-mailadres weer te geven of te verbergen. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Optie om het "Bcc" e-mailadres weer te geven of te verbergen. Standaard: false.

**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Optie om het "Bcc" e-mailadres weer te geven of te verbergen. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Haalt op of stelt de Coordinated Universal Time (UTC) offset voor de berichtdatums in. Deze eigenschap definieert het tijdzoneverschil tussen de lokale tijd en UTC.

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


Time-out voor het laden van externe bronnen

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Time-out voor het laden van externe bronnen (setter)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Haalt op of stelt de Coordinated Universal Time (UTC) offset voor de berichtdatums in. Deze eigenschap definieert het tijdzoneverschil tussen de lokale tijd en UTC.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloont huidige instantie.

**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Haalt de mapping tussen e-mailbericht en veldtekstrepresentatie op

**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - toewijzing
### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Stelt de mapping tussen e-mailbericht en veldtekstrepresentatie in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | toewijzing |

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Definieert of de originele datumheaderstring in het e-mailbericht moet worden behouden bij het opslaan of niet (standaardwaarde is true)

**Returns:**
boolean - behoud originele datum als true
### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Definieert of de originele datumheaderstring in het e-mailbericht moet worden behouden bij het opslaan of niet

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| preserveOriginalDate | boolean | behoud originele datum |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Haalt optie op om te bepalen of de documentencontainer zelf moet worden geconverteerd

**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Optie om te bepalen of de eigendomdocumenten in de documentcontainer moeten worden geconverteerd

**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Optie om te bepalen hoeveel niveaus diep de conversie moet worden uitgevoerd

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| diepte | int |  |

