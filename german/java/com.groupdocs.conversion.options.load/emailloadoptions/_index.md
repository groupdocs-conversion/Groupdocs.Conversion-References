---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von E-Mail-Dokumenten."
type: docs
weight: 18
url: /de/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Optionen zum Laden von E-Mail-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Initialisiert eine neue Instanz der Klasse [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Option zum Anzeigen oder Ausblenden der E-Mail‑Kopfzeile. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Option zum Anzeigen oder Ausblenden der E-Mail‑Kopfzeile. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Option zum Anzeigen oder Ausblenden der "from"‑E-Mail‑Adresse. |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Option zum Anzeigen oder Ausblenden der "from"‑E-Mail‑Adresse. |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Option zum Anzeigen oder Ausblenden der "to"‑E-Mail‑Adresse. |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Option zum Anzeigen oder Ausblenden der "to"‑E-Mail‑Adresse. |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Option zum Anzeigen oder Ausblenden der "Cc"‑E-Mail‑Adresse. |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Option zum Anzeigen oder Ausblenden der "Cc"‑E-Mail‑Adresse. |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Option zum Anzeigen oder Ausblenden der "Bcc"‑E-Mail‑Adresse. |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Option zum Anzeigen oder Ausblenden der "Bcc"‑E-Mail‑Adresse. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Liest oder setzt den koordinierten Weltzeit‑Offset (UTC) für die Nachrichten‑Datumsangaben. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Timeout für das Laden externer Ressourcen |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Timeout für das Laden externer Ressourcen (Setter) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Liest oder setzt den koordinierten Weltzeit‑Offset (UTC) für die Nachrichten‑Datumsangaben. |
|
|  | [deepClone()](#deepClone--) | Klont aktuelle Instanz. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Liest die Zuordnung zwischen E-Mail‑Nachricht und Feld‑Textdarstellung |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Legt die Zuordnung zwischen E-Mail-Nachricht und Feld-Textdarstellung fest |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Definiert, ob die ursprüngliche Datums-Header-Zeichenkette in der E-Mail-Nachricht beim Speichern beibehalten werden muss oder nicht (Standardwert ist true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Definiert, ob die ursprüngliche Datums-Header-Zeichenkette in der E-Mail-Nachricht beim Speichern beibehalten werden muss oder nicht |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Liefert die Option, Anhänge im Header anzuzeigen oder zu verbergen. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Setzt die Option, Anhänge im Header anzuzeigen oder zu verbergen. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Liefert die Option, den Betreff im Header anzuzeigen oder zu verbergen. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Setzt die Option, den Betreff im Header anzuzeigen oder zu verbergen |
|
|  | [isDisplaySent()](#isDisplaySent--) | Liefert die Option, das gesendete Datum/Uhrzeit im Header anzuzeigen oder zu verbergen. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Setzt die Option, das gesendete Datum/Uhrzeit im Header anzuzeigen oder zu verbergen. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Überspringt das Laden von HTTP-Ressourcen, wenn true |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Option, den E-Mail-Header anzuzeigen oder zu verbergen. Standard: true.


**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Option, den E-Mail-Header anzuzeigen oder zu verbergen. Standard: true.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Option, die "from"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: true.


**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Option, die "from"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: true.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Option, die "to"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: true.


**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Option, die "to"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: true.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Option, die "Cc"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: false.


**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Option, die "Cc"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Option, die "Bcc"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: false.


**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Option, die "Bcc"-E-Mail-Adresse anzuzeigen oder zu verbergen. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Liefert oder setzt den Coordinated Universal Time (UTC)-Offset für die Nachrichten-Daten. Diese Eigenschaft definiert den Zeitunterschied zwischen lokaler Zeit und UTC.


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


Timeout für das Laden externer Ressourcen


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Timeout für das Laden externer Ressourcen (Setter)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Liefert oder setzt den Coordinated Universal Time (UTC)-Offset für die Nachrichten-Daten. Diese Eigenschaft definiert den Zeitunterschied zwischen lokaler Zeit und UTC.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klont aktuelle Instanz.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Liest die Zuordnung zwischen E-Mail‑Nachricht und Feld‑Textdarstellung


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - Mapping

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Legt die Zuordnung zwischen E-Mail-Nachricht und Feld-Textdarstellung fest


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | Mapping |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Definiert, ob die ursprüngliche Datums-Header-Zeichenkette in der E-Mail-Nachricht beim Speichern beibehalten werden muss oder nicht (Standardwert ist true)


**Returns:**
boolean - ursprüngliches Datum beibehalten, wenn true

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Definiert, ob die ursprüngliche Datums-Header-Zeichenkette in der E-Mail-Nachricht beim Speichern beibehalten werden muss oder nicht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | preserveOriginalDate | boolean | ursprüngliches Datum beibehalten |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ruft die Option ab, um zu steuern, ob der Dokumentcontainer selbst konvertiert werden muss


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Option, um zu steuern, ob die im Dokumentcontainer enthaltenen Dokumente konvertiert werden müssen


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Option, um zu steuern, wie viele Ebenen tief die Konvertierung durchgeführt werden soll


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tiefe | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Ermittelt die Option, Anhänge in der Kopfzeile anzuzeigen oder zu verbergen. Standard: true.


**Returns:**
boolean
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Setzt die Option, Anhänge im Header anzuzeigen oder zu verbergen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| displayAttachments | boolean |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Ermittelt die Option, den Betreff in der Kopfzeile anzuzeigen oder zu verbergen. Standard: true.


**Returns:**
boolean
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Setzt die Option, den Betreff im Header anzuzeigen oder zu verbergen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| displaySubject | boolean |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Ermittelt die Option, das gesendete Datum/Uhrzeit in der Kopfzeile anzuzeigen oder zu verbergen. Standard: true.


**Returns:**
boolean
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Setzt die Option, das gesendete Datum/Uhrzeit im Header anzuzeigen oder zu verbergen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| displaySent | boolean |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Überspringt das Laden von HTTP-Ressourcen, wenn true


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| skipExternalResources | boolean |  |

