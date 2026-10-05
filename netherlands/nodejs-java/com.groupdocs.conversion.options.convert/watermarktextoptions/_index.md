---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het instellen van een tekstwatermerk op het geconverteerde document"
type: docs
weight: 45
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Opties voor het instellen van een tekstwatermerk op het geconverteerde document
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getText()](#getText--) | Watermark-tekst |
| [setText(String value)](#setText-java.lang.String-) | Watermark-tekst |
| [getWatermarkFont()](#getWatermarkFont--) | Watermark-lettertype als tekstwatermerk wordt toegepast |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Stelt het Watermark-lettertype in als tekstwatermerk wordt toegepast |
| [getColor()](#getColor--) | Watermark-letterkleur als tekstwatermerk wordt toegepast |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(int argb)](#setColor-int-) | Watermark-letterkleur als argb als tekstwatermerk wordt toegepast |
| [setColor(String colorName)](#setColor-java.lang.String-) | Watermark-letterkleurnaam als tekstwatermerk wordt toegepast |
| [setColor(Color value)](#setColor-java.awt.Color-) | Watermark-letterkleur als tekstwatermerk wordt toegepast |
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekst | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Watermark-tekst

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Watermark-tekst

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Watermark-lettertype als tekstwatermerk wordt toegepast

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Stelt het Watermark-lettertype in als tekstwatermerk wordt toegepast

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | lettertype |

### getColor() {#getColor--}
```
public final Color getColor()
```


Watermark-letterkleur als tekstwatermerk wordt toegepast

**Returns:**
java.awt.Color
### getColorInternal() {#getColorInternal--}
```
public System.Drawing.Color getColorInternal()
```




**Returns:**
com.aspose.ms.System.Drawing.Color
### setColor(int argb) {#setColor-int-}
```
public final void setColor(int argb)
```


Watermark-letterkleur als argb als tekstwatermerk wordt toegepast

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb | int |  |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Watermark-letterkleurnaam als tekstwatermerk wordt toegepast

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorName | java.lang.String |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Watermark-letterkleur als tekstwatermerk wordt toegepast

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
