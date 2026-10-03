---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Beschrijft opties voor conversie naar presentatie‑bestandstype."
type: docs
weight: 33
url: /nl/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Beschrijft opties voor conversie naar presentatie‑bestandstype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Initialiseert een nieuwe instantie van de klasse [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
|
|  | [getZoom()](#getZoom--) | Specificeert het zoomniveau in procenten. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specificeert het zoomniveau in procenten. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Initialiseert een nieuwe instantie van de klasse [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specificeert het zoomniveau in procenten. Standaard is 100.
Standaardzoom wordt ondersteund tot Microsoft PowerPoint 2010. Vanaf Microsoft PowerPoint 2013 wordt de standaardzoom niet langer op het document ingesteld; in plaats daarvan lijkt deze de zoomfactor van het laatst geopende document te gebruiken.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specificeert het zoomniveau in procenten. Standaard is 100.
Standaardzoom wordt ondersteund tot Microsoft PowerPoint 2010. Vanaf Microsoft PowerPoint 2013 wordt de standaardzoom niet langer op het document ingesteld; in plaats daarvan lijkt deze de zoomfactor van het laatst geopende document te gebruiken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

