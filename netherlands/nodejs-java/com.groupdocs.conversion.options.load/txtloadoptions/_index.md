---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van Txt-documenten."
type: docs
weight: 38
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van Txt-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TxtLoadOptions()](#TxtLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. |
| [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. |
| [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Geeft of stelt de voorkeursoptie in voor de behandeling van een achterliggende spatie. |
| [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Geeft of stelt de voorkeursoptie in voor de behandeling van een achterliggende spatie. |
| [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Geeft of stelt de voorkeursoptie in voor de behandeling van een leidende spatie. |
| [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Geeft of stelt de voorkeursoptie in voor de behandeling van een leidende spatie. |
| [getEncoding()](#getEncoding--) | Geeft of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Geeft of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Geeft of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. |
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).

### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Bestandstype van invoerdocument

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. De standaardwaarde is true.

--------------------

Als deze optie is ingesteld op false, detecteert het lijstherkenningsalgoritme lijstparagrafen wanneer lijstnummers eindigen op een punt, rechte haak of opsommingsteken (zoals "\\u2022", "\*", "-" of "o").

Als deze optie is ingesteld op true, worden witruimtes ook gebruikt als scheidingstekens voor lijstnummers: het lijstherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel witruimtes als punt (".") symbolen.

**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. De standaardwaarde is true.

--------------------

Als deze optie is ingesteld op false, detecteert het lijstherkenningsalgoritme lijstparagrafen wanneer lijstnummers eindigen op een punt, rechte haak of opsommingsteken (zoals "\\u2022", "\*", "-" of "o").

Als deze optie is ingesteld op true, worden witruimtes ook gebruikt als scheidingstekens voor lijstnummers: het lijstherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel witruimtes als punt (".") symbolen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Geeft of stelt de voorkeursoptie in voor de behandeling van een achterliggende spatie. Standaardwaarde is [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim).

**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Geeft of stelt de voorkeursoptie in voor de behandeling van een achterliggende spatie. Standaardwaarde is [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Geeft of stelt de voorkeursoptie in voor de behandeling van een leidende spatie. Standaardwaarde is [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent).

**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Geeft of stelt de voorkeursoptie in voor de behandeling van een leidende spatie. Standaardwaarde is [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Geeft of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. Kan null zijn. Standaard is null.

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


Geeft of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. Kan null zijn. Standaard is null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setEncoding(String charsetName) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String charsetName)
```


Geeft of stelt de codering in die wordt gebruikt bij het laden van een Txt-document. Kan null zijn. Standaard is null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charsetName | java.lang.String |  |

