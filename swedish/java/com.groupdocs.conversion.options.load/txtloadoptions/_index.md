---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för att läsa in Txt-dokument."
type: docs
weight: 34
url: /sv/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Alternativ för att läsa in Txt-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Initierar en ny instans av klassen [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Tillåter att ange hur numrerade listobjekt identifieras när ett vanligtextdokument konverteras. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Tillåter att ange hur numrerade listobjekt identifieras när ett vanligtextdokument konverteras. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Hämtar eller anger föredragen inställning för hantering av efterföljande mellanslag. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Hämtar eller anger föredragen inställning för hantering av efterföljande mellanslag. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Hämtar eller anger föredragen inställning för hantering av inledande mellanslag. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Hämtar eller anger föredragen inställning för hantering av inledande mellanslag. |
|
|  | [getEncoding()](#getEncoding--) | Hämtar eller anger kodningen som ska användas vid inläsning av Txt-dokument. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Hämtar eller anger kodningen som ska användas vid inläsning av Txt-dokument. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Initierar en ny instans av klassen [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Dokumentfiltyp för inmatning


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Tillåter att ange hur numrerade listobjekt identifieras när ett vanligtextdokument konverteras.
Standardvärdet är true.

<br />

*** ** * ** ***

Om detta alternativ är satt till false, upptäcker listigenkänningsalgoritmen listparagrafer när listnummer slutar med
antingen punkt, högra hakparentes eller punktlistsymboler (såsom "\u2022", "*", "-" eller "o").

Om detta alternativ är satt till true används mellanslag också som avgränsare för listnummer:
Listigenkänningsalgoritmen för arabiskt stilnumrering (1., 1.1.2.) använder både mellanslag och punkt (".")-symboler.

<br />



**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Tillåter att ange hur numrerade listobjekt identifieras när ett vanligtextdokument konverteras.
Standardvärdet är true.

<br />

*** ** * ** ***

Om detta alternativ är satt till false, upptäcker listigenkänningsalgoritmen listparagrafer när listnummer slutar med
antingen punkt, högra hakparentes eller punktlistsymboler (såsom "\u2022", "*", "-" eller "o").

Om detta alternativ är satt till true används mellanslag också som avgränsare för listnummer:
Listigenkänningsalgoritmen för arabiskt stilnumrering (1., 1.1.2.) använder både mellanslag och punkt (".")-symboler.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Hämtar eller anger föredragen inställning för hantering av efterföljande mellanslag.
Standardvärdet är [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Hämtar eller anger föredragen inställning för hantering av efterföljande mellanslag.
Standardvärdet är [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Hämtar eller anger föredragen inställning för hantering av inledande mellanslag.
Standardvärdet är [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Hämtar eller anger föredragen inställning för hantering av inledande mellanslag.
Standardvärdet är [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Hämtar eller anger kodningen som ska användas vid inläsning av Txt-dokument. Kan vara null. Standard är null.


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


Hämtar eller anger kodningen som ska användas vid inläsning av Txt-dokument. Kan vara null. Standard är null.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

