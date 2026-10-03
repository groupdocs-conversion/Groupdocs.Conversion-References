---
title: "RtfOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för konvertering till RTF-filtyp."
type: docs
weight: 39
url: /sv/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Alternativ för konvertering till RTF-filtyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Anger om nyckelorden för "old readers" skrivs till RTF eller inte. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Anger om nyckelorden för "old readers" skrivs till RTF eller inte. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Anger om nyckelorden för "old readers" skrivs till RTF eller inte.
Detta kan påverka storleken på RTF-dokumentet avsevärt. Standard är False.


**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Anger om nyckelorden för "old readers" skrivs till RTF eller inte.
Detta kan påverka storleken på RTF-dokumentet avsevärt. Standard är False.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

