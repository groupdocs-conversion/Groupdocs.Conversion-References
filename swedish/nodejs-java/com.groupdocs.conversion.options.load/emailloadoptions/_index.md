---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inläsning av e‑postdokument."
type: docs
weight: 19
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Alternativ för inläsning av e‑postdokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmailLoadOptions()](#EmailLoadOptions--) | Initierar en ny instans av [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDisplayHeader()](#getDisplayHeader--) | Alternativ för att visa eller dölja e-postrubriken. |
| [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Alternativ för att visa eller dölja e-postrubriken. |
| [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Alternativ för att visa eller dölja \"från\" e-postadress. |
| [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Alternativ för att visa eller dölja \"från\" e-postadress. |
| [getDisplayEmailAddress()](#getDisplayEmailAddress--) | Alternativ för att visa eller dölja e-postadress. |
| [setDisplayEmailAddress(boolean value)](#setDisplayEmailAddress-boolean-) | Alternativ för att visa eller dölja e-postadress. |
| [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Alternativ för att visa eller dölja \"till\" e-postadress. |
| [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Alternativ för att visa eller dölja \"till\" e-postadress. |
| [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Alternativ för att visa eller dölja \"Cc\" e-postadress. |
| [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Alternativ för att visa eller dölja \"Cc\" e-postadress. |
| [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Alternativ för att visa eller dölja \"Bcc\" e-postadress. |
| [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Alternativ för att visa eller dölja \"Bcc\" e-postadress. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Hämtar eller anger den koordinerade universella tiden (UTC) förskjutning för meddelandedatum. |
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Timeout för att ladda externa resurser |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Timeout för att ladda externa resurser (setter) |
| [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Hämtar eller anger den koordinerade universella tiden (UTC) förskjutning för meddelandedatum. |
| [deepClone()](#deepClone--) | Klonar aktuell instans. |
| [getFieldTextMap()](#getFieldTextMap--) | Hämtar mappningen mellan e-postmeddelande och fälttextrepresentation |
| [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Ställer in mappningen mellan e-postmeddelande och fälttextrepresentation |
| [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Definierar om det behövs att behålla den ursprungliga datumhuvudsträngen i e-postmeddelandet vid sparande eller inte (Standardvärdet är true) |
| [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Definierar om det behövs att behålla den ursprungliga datumhuvudsträngen i e-postmeddelandet vid sparande eller inte |
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


Initierar en ny instans av [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) klass.

### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Inmatningsdokumentets filtyp

**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Alternativ för att visa eller dölja e-posthuvudet. Standard: true.

**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Alternativ för att visa eller dölja e-posthuvudet. Standard: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Alternativ för att visa eller dölja \"från\" e-postadress. Standard: true.

**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Alternativ för att visa eller dölja \"från\" e-postadress. Standard: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayEmailAddress() {#getDisplayEmailAddress--}
```
public final boolean getDisplayEmailAddress()
```


Alternativ för att visa eller dölja e-postadress. Standard: true.

**Returns:**
boolean
### setDisplayEmailAddress(boolean value) {#setDisplayEmailAddress-boolean-}
```
public final void setDisplayEmailAddress(boolean value)
```


Alternativ för att visa eller dölja e-postadress. Standard: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Alternativ för att visa eller dölja \"till\" e-postadress. Standard: true.

**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Alternativ för att visa eller dölja \"till\" e-postadress. Standard: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Alternativ för att visa eller dölja \"Cc\" e-postadress. Standard: false.

**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Alternativ för att visa eller dölja \"Cc\" e-postadress. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Alternativ för att visa eller dölja \"Bcc\" e-postadress. Standard: false.

**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Alternativ för att visa eller dölja \"Bcc\" e-postadress. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Hämtar eller anger den koordinerade universella tiden (UTC) förskjutning för meddelandedatumen. Denna egenskap definierar tidszonskillnaden mellan lokal tid och UTC.

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


Timeout för att ladda externa resurser

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Timeout för att ladda externa resurser (setter)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Hämtar eller anger den koordinerade universella tiden (UTC) förskjutning för meddelandedatumen. Denna egenskap definierar tidszonskillnaden mellan lokal tid och UTC.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klonar aktuell instans.

**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Hämtar mappningen mellan e-postmeddelande och fälttextrepresentation

**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - mappning
### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Ställer in mappningen mellan e-postmeddelande och fälttextrepresentation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | mappning |

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Definierar om det behövs att behålla den ursprungliga datumhuvudsträngen i e-postmeddelandet vid sparande eller inte (Standardvärdet är true)

**Returns:**
boolean - bevara ursprungligt datum om true
### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Definierar om det behövs att behålla den ursprungliga datumhuvudsträngen i e-postmeddelandet vid sparande eller inte

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| preserveOriginalDate | boolean | bevara ursprungligt datum |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Hämtar alternativ för att kontrollera om dokumentbehållaren själv måste konverteras

**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Alternativ för att styra om de ägda dokumenten i dokumentbehållaren måste konverteras

**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Alternativ för att styra hur många nivåer i djupet konverteringen ska utföras

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| djup | int |  |

