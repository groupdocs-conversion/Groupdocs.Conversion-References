---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för konvertering till kalkylbladsfiltyp."
type: docs
weight: 40
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Alternativ för konvertering till kalkylbladsfiltyp.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Initierar en ny instans av klassen [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPassword()](#getPassword--) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [getZoom()](#getZoom--) | Anger zoomnivån i procent. |
| [setZoom(int value)](#setZoom-int-) | Anger zoomnivån i procent. |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Initierar en ny instans av klassen [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).

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
| value | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Anger zoomnivån i procent. Standard är 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Anger zoomnivån i procent. Standard är 100.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

