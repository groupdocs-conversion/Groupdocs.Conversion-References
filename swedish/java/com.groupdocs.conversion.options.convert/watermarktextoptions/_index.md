---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för inställning av textvattenstämpel till det konverterade dokumentet"
type: docs
weight: 45
url: /sv/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
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
|  | [getText()](#getText--) | Vattenstämpeltext |
|
|  | [setText(String value)](#setText-java.lang.String-) | Vattenstämpeltext |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Vattenstämpelfont om textvattenstämpel har tillämpats |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Ställer in vattenstämpelfont om textvattenstämpel har tillämpats |
|
|  | [getColor()](#getColor--) | Vattenstämpelfontfärg om textvattenstämpel har tillämpats |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Vattenstämpelfontfärg om textvattenstämpel har tillämpats |
|
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
| värde | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Vattenstämpelfont om textvattenstämpel har tillämpats


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Ställer in vattenstämpelfont om textvattenstämpel har tillämpats


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | teckensnitt |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Vattenstämpelfontfärg om textvattenstämpel har tillämpats


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


Vattenstämpelfontfärg om textvattenstämpel har tillämpats


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
