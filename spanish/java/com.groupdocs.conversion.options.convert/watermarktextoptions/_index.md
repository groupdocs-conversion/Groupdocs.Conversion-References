---
title: "WatermarkTextOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para establecer la marca de agua de texto en el documento convertido"
type: docs
weight: 45
url: /es/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Opciones para establecer la marca de agua de texto en el documento convertido

## Constructores

| Constructor | Descripción |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Texto de marca de agua |
|
|  | [setText(String value)](#setText-java.lang.String-) | Texto de marca de agua |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Fuente de marca de agua si se aplica una marca de agua de texto |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Establece la fuente de la marca de agua si se aplica una marca de agua de texto |
|
|  | [getColor()](#getColor--) | Color de fuente de la marca de agua si se aplica una marca de agua de texto |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Color de fuente de la marca de agua si se aplica una marca de agua de texto |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Texto de marca de agua


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Texto de marca de agua


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Fuente de marca de agua si se aplica una marca de agua de texto


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Establece la fuente de la marca de agua si se aplica una marca de agua de texto


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | fuente |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Color de fuente de la marca de agua si se aplica una marca de agua de texto


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


Color de fuente de la marca de agua si se aplica una marca de agua de texto


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
