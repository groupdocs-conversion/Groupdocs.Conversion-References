---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für das Festlegen eines Textwasserzeichens für das konvertierte Dokument"
type: docs
weight: 45
url: /de/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Optionen für das Festlegen eines Textwasserzeichens für das konvertierte Dokument

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Wasserzeichen-Text |
|
|  | [setText(String value)](#setText-java.lang.String-) | Wasserzeichen-Text |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Wasserzeichen-Schriftart, wenn ein Textwasserzeichen angewendet wird |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Setzt die Wasserzeichen-Schriftart, wenn ein Textwasserzeichen angewendet wird |
|
|  | [getColor()](#getColor--) | Wasserzeichen-Schriftfarbe, wenn ein Textwasserzeichen angewendet wird |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Wasserzeichen-Schriftfarbe, wenn ein Textwasserzeichen angewendet wird |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Text | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Wasserzeichen-Text


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Wasserzeichen-Text


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Wasserzeichen-Schriftart, wenn ein Textwasserzeichen angewendet wird


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Setzt die Wasserzeichen-Schriftart, wenn ein Textwasserzeichen angewendet wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | Schriftart |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Wasserzeichen-Schriftfarbe, wenn ein Textwasserzeichen angewendet wird


**Returns:**
java.awt.Color
### getColorInternal() {#getColorInternal--}
```
public System.Drawing.Color getColorInternal()
```




**Returns:**
com.aspose.ms.System.Drawing.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Wasserzeichen-Schriftfarbe, wenn ein Textwasserzeichen angewendet wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
