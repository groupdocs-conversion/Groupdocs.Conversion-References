---
title: "WatermarkTextOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para configurar la marca de agua de texto en el documento convertido"
type: docs
weight: 45
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Opciones para configurar la marca de agua de texto en el documento convertido
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | Texto de marca de agua |
| [setText(String value)](#setText-java.lang.String-) | Texto de marca de agua |
| [getWatermarkFont()](#getWatermarkFont--) | Fuente de marca de agua si se aplica la marca de agua de texto |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Establece la fuente de marca de agua si se aplica la marca de agua de texto |
| [getColor()](#getColor--) | Color de fuente de marca de agua si se aplica la marca de agua de texto |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(int argb)](#setColor-int-) | Color de fuente de marca de agua como argb si se aplica la marca de agua de texto |
| [setColor(String colorName)](#setColor-java.lang.String-) | Nombre del color de fuente de marca de agua si se aplica la marca de agua de texto |
| [setColor(Color value)](#setColor-java.awt.Color-) | Color de fuente de marca de agua si se aplica la marca de agua de texto |
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


Fuente de marca de agua si se aplica la marca de agua de texto

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Establece la fuente de marca de agua si se aplica la marca de agua de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | fuente |

### getColor() {#getColor--}
```
public final Color getColor()
```


Color de fuente de marca de agua si se aplica la marca de agua de texto

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


Color de fuente de marca de agua como argb si se aplica la marca de agua de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | int |  |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Nombre del color de fuente de marca de agua si se aplica la marca de agua de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorName | java.lang.String |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Color de fuente de marca de agua si se aplica la marca de agua de texto

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
