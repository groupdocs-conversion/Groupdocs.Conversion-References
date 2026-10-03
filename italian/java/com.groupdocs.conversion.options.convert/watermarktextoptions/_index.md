---
title: "WatermarkTextOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per impostare la filigrana di testo al documento convertito"
type: docs
weight: 45
url: /it/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Opzioni per impostare la filigrana di testo al documento convertito

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | Testo filigrana |
|
|  | [setText(String value)](#setText-java.lang.String-) | Testo filigrana |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Carattere della filigrana se viene applicata una filigrana testuale |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Imposta il carattere della filigrana se viene applicata una filigrana testuale |
|
|  | [getColor()](#getColor--) | Colore del carattere della filigrana se viene applicata una filigrana testuale |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Colore del carattere della filigrana se viene applicata una filigrana testuale |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Testo filigrana


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Testo filigrana


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Carattere della filigrana se viene applicata una filigrana testuale


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Imposta il carattere della filigrana se viene applicata una filigrana testuale


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | carattere |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Colore del carattere della filigrana se viene applicata una filigrana testuale


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


Colore del carattere della filigrana se viene applicata una filigrana testuale


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
