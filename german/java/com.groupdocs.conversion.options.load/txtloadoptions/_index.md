---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Txt-Dokumenten."
type: docs
weight: 34
url: /de/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Optionen zum Laden von Txt-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Initialisiert eine neue Instanz der Klasse [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn ein Nur-Text-Dokument konvertiert wird. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn ein Nur-Text-Dokument konvertiert wird. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Liest oder setzt die bevorzugte Option für die Behandlung von nachgestellten Leerzeichen. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Liest oder setzt die bevorzugte Option für die Behandlung von nachgestellten Leerzeichen. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Liest oder setzt die bevorzugte Option für die Behandlung von vorangestellten Leerzeichen. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Liest oder setzt die bevorzugte Option für die Behandlung von vorangestellten Leerzeichen. |
|
|  | [getEncoding()](#getEncoding--) | Liest oder setzt die Kodierung, die beim Laden eines Txt-Dokuments verwendet wird. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Liest oder setzt die Kodierung, die beim Laden eines Txt-Dokuments verwendet wird. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn ein Nur-Text-Dokument konvertiert wird.
Der Standardwert ist true.

<br />

*** ** * ** ***

Wenn diese Option auf false gesetzt ist, erkennt der Listen-Erkennungsalgorithmus Listenkapitel, wenn Listennummern enden mit
entweder Punkt, rechte Klammer oder Aufzählungssymbole (wie "\\u2022", "\\*", "-" oder "o").

Wenn diese Option auf true gesetzt ist, werden Leerzeichen ebenfalls als Trennzeichen für Listennummern verwendet:
Der Listen-Erkennungsalgorithmus für arabische Nummerierung (1., 1.1.2.) verwendet sowohl Leerzeichen als auch Punkt (\".\")-Symbole.

<br />



**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Ermöglicht die Angabe, wie nummerierte Listenelemente erkannt werden, wenn ein Nur-Text-Dokument konvertiert wird.
Der Standardwert ist true.

<br />

*** ** * ** ***

Wenn diese Option auf false gesetzt ist, erkennt der Listen-Erkennungsalgorithmus Listenkapitel, wenn Listennummern enden mit
entweder Punkt, rechte Klammer oder Aufzählungssymbole (wie "\\u2022", "\\*", "-" oder "o").

Wenn diese Option auf true gesetzt ist, werden Leerzeichen ebenfalls als Trennzeichen für Listennummern verwendet:
Der Listen-Erkennungsalgorithmus für arabische Nummerierung (1., 1.1.2.) verwendet sowohl Leerzeichen als auch Punkt (\".\")-Symbole.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Liest oder setzt die bevorzugte Option für die Behandlung von nachgestellten Leerzeichen.
Standardwert ist [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Liest oder setzt die bevorzugte Option für die Behandlung von nachgestellten Leerzeichen.
Standardwert ist [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Liest oder setzt die bevorzugte Option für die Behandlung von vorangestellten Leerzeichen.
Standardwert ist [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Liest oder setzt die bevorzugte Option für die Behandlung von vorangestellten Leerzeichen.
Standardwert ist [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Liest oder setzt die Kodierung, die beim Laden eines Txt-Dokuments verwendet wird. Kann null sein. Standard ist null.


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


Liest oder setzt die Kodierung, die beim Laden eines Txt-Dokuments verwendet wird. Kann null sein. Standard ist null.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

