---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van Txt‑documenten."
type: docs
weight: 34
url: /nl/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van Txt‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Staat toe op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Staat toe op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Haalt op of stelt de voorkeuroptie in voor het afhandelen van een afsluitende spatie. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Haalt op of stelt de voorkeuroptie in voor het afhandelen van een afsluitende spatie. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Haalt op of stelt de voorkeuroptie in voor het afhandelen van een leidende spatie. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Haalt op of stelt de voorkeuroptie in voor het afhandelen van een leidende spatie. |
|
|  | [getEncoding()](#getEncoding--) | Haalt op of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Haalt op of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Invoerdocumentbestandstype


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Staat toe op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd.
De standaardwaarde is true.

<br />

*** ** * ** ***

Als deze optie op false is ingesteld, detecteert het lijstenherkenningsalgoritme lijstparagrafen wanneer lijstnummers eindigen op
een punt, rechte haak of opsommingstekens (zoals "\u2022", "*", "-" of "o").

Als deze optie op true is ingesteld, worden spaties ook gebruikt als scheidingsteken voor lijstnummers:
Het lijstenherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel spaties als punt (".") tekens.

<br />



**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Staat toe op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd.
De standaardwaarde is true.

<br />

*** ** * ** ***

Als deze optie op false is ingesteld, detecteert het lijstenherkenningsalgoritme lijstparagrafen wanneer lijstnummers eindigen op
een punt, rechte haak of opsommingstekens (zoals "\u2022", "*", "-" of "o").

Als deze optie op true is ingesteld, worden spaties ook gebruikt als scheidingsteken voor lijstnummers:
Het lijstenherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel spaties als punt (".") tekens.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Haalt op of stelt de voorkeuroptie in voor het afhandelen van een afsluitende spatie.
Standaardwaarde is [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Haalt op of stelt de voorkeuroptie in voor het afhandelen van een afsluitende spatie.
Standaardwaarde is [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Haalt op of stelt de voorkeuroptie in voor het afhandelen van een leidende spatie.
Standaardwaarde is [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Haalt op of stelt de voorkeuroptie in voor het afhandelen van een leidende spatie.
Standaardwaarde is [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Haalt of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. Kan null zijn. Standaard is null.


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


Haalt of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. Kan null zijn. Standaard is null.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

