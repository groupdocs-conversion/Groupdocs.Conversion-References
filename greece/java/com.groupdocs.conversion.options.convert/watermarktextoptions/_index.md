---
title: "WatermarkTextOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για ρύθμιση υδατογραφήματος κειμένου στο μετατρεπόμενο έγγραφο"
type: docs
weight: 45
url: /el/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Επιλογές για ρύθμιση υδατογραφήματος κειμένου στο μετατρεπόμενο έγγραφο

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Κείμενο υδατογράφησης |
|
|  | [setText(String value)](#setText-java.lang.String-) | Κείμενο υδατογράφησης |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Γραμματοσειρά υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Ορίζει τη γραμματοσειρά υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης |
|
|  | [getColor()](#getColor--) | Χρώμα γραμματοσειράς υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Χρώμα γραμματοσειράς υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Κείμενο υδατογράφησης


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Κείμενο υδατογράφησης


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Γραμματοσειρά υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Ορίζει τη γραμματοσειρά υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | font |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Χρώμα γραμματοσειράς υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης


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


Χρώμα γραμματοσειράς υδατογράφησης εάν εφαρμόζεται κείμενο υδατογράφησης


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
