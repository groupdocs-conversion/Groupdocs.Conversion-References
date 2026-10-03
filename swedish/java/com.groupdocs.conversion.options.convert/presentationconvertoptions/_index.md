---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Beskriver alternativ för konvertering till Presentation-filtyp."
type: docs
weight: 33
url: /sv/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Beskriver alternativ för konvertering till Presentation-filtyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Initierar en ny instans av klassen [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
|
|  | [getZoom()](#getZoom--) | Anger zoomnivån i procent. |
|
|  | [setZoom(int value)](#setZoom-int-) | Anger zoomnivån i procent. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Initierar en ny instans av klassen [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Anger zoomnivån i procent. Standard är 100.
Standardzoom stöds upp till Microsoft Powerpoint 2010. Från och med Microsoft Powerpoint 2013 sätts standardzoom inte längre på dokumentet, utan det verkar använda zoomfaktorn från det senaste dokumentet som öppnades.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Anger zoomnivån i procent. Standard är 100.
Standardzoom stöds upp till Microsoft Powerpoint 2010. Från och med Microsoft Powerpoint 2013 sätts standardzoom inte längre på dokumentet, utan det verkar använda zoomfaktorn från det senaste dokumentet som öppnades.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

