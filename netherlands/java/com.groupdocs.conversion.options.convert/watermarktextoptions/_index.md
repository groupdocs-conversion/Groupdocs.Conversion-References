---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het instellen van een tekstwatermerk op het geconverteerde document."
type: docs
weight: 45
url: /nl/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Opties voor het instellen van een tekstwatermerk op het geconverteerde document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Watermerktekst |
|
|  | [setText(String value)](#setText-java.lang.String-) | Watermerktekst |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Watermerklettertype als een tekstwatermerk wordt toegepast |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Stelt het watermerklettertype in als een tekstwatermerk wordt toegepast |
|
|  | [getColor()](#getColor--) | Watermerkletterkleur als een tekstwatermerk wordt toegepast |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Watermerkletterkleur als een tekstwatermerk wordt toegepast |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Watermerktekst


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Watermerktekst


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Watermerklettertype als een tekstwatermerk wordt toegepast


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Stelt het watermerklettertype in als een tekstwatermerk wordt toegepast


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | font |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Watermerkletterkleur als een tekstwatermerk wordt toegepast


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


Watermerkletterkleur als een tekstwatermerk wordt toegepast


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
