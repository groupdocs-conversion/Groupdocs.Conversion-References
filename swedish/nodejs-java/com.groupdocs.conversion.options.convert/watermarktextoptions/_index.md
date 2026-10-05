---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inställning av textvattenstämpel till det konverterade dokumentet"
type: docs
weight: 45
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Alternativ för inställning av textvattenstämpel till det konverterade dokumentet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Vattenstämpeltext |
| [setText(String value)](#setText-java.lang.String-) | Vattenstämpeltext |
| [getWatermarkFont()](#getWatermarkFont--) | Vattenstämpelns teckensnitt om textvattenstämpel tillämpas |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Ställer in vattenstämpelns teckensnitt om textvattenstämpel tillämpas |
| [getColor()](#getColor--) | Vattenstämpelns teckensnittsfärg om textvattenstämpel tillämpas |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(int argb)](#setColor-int-) | Vattenstämpelns teckensnittsfärg som argb om textvattenstämpel tillämpas |
| [setColor(String colorName)](#setColor-java.lang.String-) | Vattenstämpelns teckensnittsfärgnamn om textvattenstämpel tillämpas |
| [setColor(Color value)](#setColor-java.awt.Color-) | Vattenstämpelns teckensnittsfärg om textvattenstämpel tillämpas |
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Vattenstämpeltext

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Vattenstämpeltext

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Vattenstämpelns teckensnitt om textvattenstämpel tillämpas

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Ställer in vattenstämpelns teckensnitt om textvattenstämpel tillämpas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | teckensnitt |

### getColor() {#getColor--}
```
public final Color getColor()
```


Vattenstämpelns teckensnittsfärg om textvattenstämpel tillämpas

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


Vattenstämpelns teckensnittsfärg som argb om textvattenstämpel tillämpas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int |  |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Vattenstämpelns teckensnittsfärgnamn om textvattenstämpel tillämpas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorName | java.lang.String |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Vattenstämpelns teckensnittsfärg om textvattenstämpel tillämpas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
